# vsc_md_preview_theme

VSCode Markdown Preview Dracula Theme

## How to use

Search **Markdown:Styles** in setting, add `https://cdn.jsdelivr.net/gh/xrunes/vsc_md_preview_theme/style.css`.

Or modify **setting.json**, add

```json
"markdown.styles": [
        "https://cdn.jsdelivr.net/gh/xrunes/vsc_md_preview_theme/style.css"
    ],
```

## Network in Chia

如果你在中国，jsdelivr可能会被屏蔽，可以使用[镜像](https://cdn.jsdmirror.com/)代替，例如`https://cdn.jsdmirror.cn/gh/xrunes/vsc_md_preview_theme/style.css`

镜像站作者的[博客](https://www.codeqihan.com/post/zi-zhi-de-yi-ge-jsdelivr-jing-xiang-fen-xiang/)

## Attention

- **markdown.styles** only support positive path, DO NOT support absolute path. This is why I use online URL.
- Eferencing style.css through `https://raw.githubusercontent.com/xrunes/vsc_md_preview_theme/refs/heads/master/style.css` DO NOT work either. It seems Github don't support [https://github.com/microsoft/vscode/issues/8287#issuecomment-230021773](https://github.com/microsoft/vscode/issues/8287#issuecomment-230021773)