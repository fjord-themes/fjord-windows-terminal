# Fjord Theme for Windows Terminal

A dusk-blue base with soft leaf-green accents, cyan selections, and crisp blue/cyan separation for Windows Terminal.


## 🎨 Color Palette

### Core Colors

| Color | Name |
| ---- | ----------------- |
| ![background](https://img.shields.io/badge/%231B2532-1B2532) | **background** |
| ![backgroundAlt](https://img.shields.io/badge/%23222E3F-222E3F) | **backgroundAlt** |
| ![surface](https://img.shields.io/badge/%231F2A39-1F2A39) | **surface** |
| ![line](https://img.shields.io/badge/%23233141-233141) | **line** |
| ![foreground](https://img.shields.io/badge/%23E8F0F3-E8F0F3) | **foreground** |
| ![muted](https://img.shields.io/badge/%236C7A86-6C7A86) | **muted** |
| ![mutedDim](https://img.shields.io/badge/%2351606B-51606B) | **mutedDim** |

### Accent Colors

| Color | Name |
| ---- | ---------------------------- |
| ![green](https://img.shields.io/badge/%239DD99A-9DD99A) | **green** _(primary accent)_ |
| ![blue](https://img.shields.io/badge/%235DA6EA-5DA6EA) | **blue** |
| ![yellow](https://img.shields.io/badge/%23FFD285-FFD285) | **yellow** |
| ![purple](https://img.shields.io/badge/%23B9A0F8-B9A0F8) | **purple** |
| ![red](https://img.shields.io/badge/%23F37C7C-F37C7C) | **red** |
| ![cyan](https://img.shields.io/badge/%23B8E7E9-B8E7E9) | **cyan** |

## 📦 Installation


### Manual Installation


1. Open Windows Terminal Settings (`Ctrl+Shift+,`) and click **Open JSON file** in the bottom-left corner
2. Add the Fjord theme to your `profiles.defaults`:
```json
{
"colorScheme": "Fjord"
}
```
3. Add the color scheme to your `schemes` array:
```json
{
"name": "Fjord",
"background": "#1B2532",
"foreground": "#E8F0F3",
"selectionBackground": "#B8E7E9",
"cursorColor": "#9DD99A",
"black": "#212128",
"red": "#F37C7C",
"green": "#9DD99A",
"yellow": "#FFD285",
"blue": "#5DA6EA",
"purple": "#B9A0F8",
"cyan": "#B8E7E9",
"white": "#E8F0F3",
"brightBlack": "#51606B",
"brightRed": "#FF9B9B",
"brightGreen": "#A3D5A0",
"brightYellow": "#FFE0A3",
"brightBlue": "#7BB8FF",
"brightPurple": "#D4C6F7",
"brightCyan": "#A1E9DE",
"brightWhite": "#EFFAFF"
}
```
4. Save the settings and the theme will be applied


## 🔧 Configuration

The theme includes:

- Complete 16-color terminal palette
- Optimized background and foreground colors
- Custom selection and cursor colors
- Enhanced readability with proper contrast ratios
## 🔄 Updates

This theme is automatically generated from [fjord-core](https://github.com/fjord-themes/fjord-core) and deployed on every release. For an overview of all supported platforms and the full color palette, visit the [Fjord GitHub page](https://github.com/fjord-themes).
## ☕ Support My Work

If you enjoy the Fjord theme and find it useful, consider supporting my work:

[![Buy Me A Coffee](https://img.shields.io/badge/Buy_Me_A_Coffee-99dd9a?style=for-the-badge&logo=buy-me-a-coffee&logoColor=FFD285&logoSize=auto&labelColor=1B2532)](https://buymeacoffee.com/jshuntley)
## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.
## 🤝 Contributing

For theme suggestions or issues, please open an issue on the [Fjord GitHub page](https://github.com/fjord-themes).