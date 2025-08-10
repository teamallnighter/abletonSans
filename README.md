# Ableton Sans Webfont Package

Easily use Ableton Sans fonts on your website via jsDelivr CDN!

## Quick Start

Add this line to your HTML `<head>` to load all font weights and styles:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/teamallnighter/abletonSans@latest/abletonSans.css">
```

This will load all `@font-face` rules for the Ableton Sans family, with font files delivered directly from this GitHub repo via jsDelivr.

## Usage Example

After including the CSS, you can use the fonts in your CSS like this:

```css
body {
	font-family: 'AbletonSans', Arial, sans-serif;
}

.bold {
	font-family: 'AbletonSansBold', Arial, sans-serif;
	font-weight: 700;
}

.light {
	font-family: 'AbletonSansLight', Arial, sans-serif;
	font-weight: 300;
}

.medium {
	font-family: 'AbletonSansMedium', Arial, sans-serif;
	font-weight: 500;
}
```

## Font Files Included

- AbletonSans-Regular.woff
- AbletonSans-Italic.woff
- AbletonSans-Bold.woff
- AbletonSans-BoldItalic.woff
- AbletonSans-ExtraLight.woff
- AbletonSans-ExtraLightItalic.woff
- AbletonSans-Light.woff
- AbletonSans-LightItalic.woff
- AbletonSans-Medium.woff
- AbletonSans-MediumItalic.woff
- AbletonSansBold-Regular.woff
- AbletonSansLight-Regular.woff
- AbletonSansMedium-Regular.woff

## How it Works

- The `abletonSans.css` file contains all the `@font-face` rules, each referencing the font files via jsDelivr CDN URLs.
- When you include the CSS file from jsDelivr, all fonts are available for use in your site styles.

## Custom Usage

If you want to reference a specific font file directly, use this format:

```
https://cdn.jsdelivr.net/gh/teamallnighter/abletonSans@latest/abletonSans/[font-file-name.woff]
```

Example:
```
https://cdn.jsdelivr.net/gh/teamallnighter/abletonSans@latest/abletonSans/AbletonSans-Regular.woff
```

---

Enjoy using Ableton Sans on the web!
