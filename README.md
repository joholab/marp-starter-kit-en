# marp-starter-kit-en

## Environment

- Windows 10
- VSCode

## Folder Structure

```
marp-starter-kit-en/
    ├ images/
    │   ├ Image files
    │   └ ・・・    
    ├ themes/
    │   └ mydefault.css（Custom theme）
    ├ README.md（This file）
    └ slides.md（Slides）
```

## Custome theme

- University Logo
- `Default` theme + `gaia` font size
- Default without slide class: Top-left align
- `lead`: Middle-center align

## How to use the custom theme

- Open `slides.md`
- Type `Ctrl+,` to open config setting
- Search for `marp`
    - Select Add at `Markdown › Marp: Themes`
    - Type `themes\mydefault.css`
    - Select OK
    - Check `Markdown › Marp: Enable HTML`

## How to make two-columns layout

```
<div class="row">
<div class="column">

Left column content

</div>
<div class="column">

Right column content

</div>
</div>
```

## How to remove footer from a slide

```
---
<!-- _footer: '' -->
```

## Broken PDF

- If your PDF export does not look the same as VSCode Preview, then check the encoding of your markdown files
    - "UTF-8 with BOM" should be saved with "UTF-8"

## Other resources

- https://marp.app/
- https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode
