# night.css

A dark-first reading theme designed for low-light environments. It uses a warm, low-luminance background, slightly larger 19px text, and a narrower 62ch measure to reduce eye strain.

## Usage

Link either the Georgia or Gelasio version in your `<head>`:

```html
<!-- Georgia (Native) -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ceiling-lizard/warm.css@main/night-georgia.css">

<!-- Gelasio (Web Font) -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ceiling-lizard/warm.css@main/night-gelasio.css">
```

## Features

- Dark-First: Optimized for night reading with an off-black background and dimmed cream text.
- Verse Support: Includes .verse, .translation, and .verse-num classes for scripture or recited text.
- Automatic Light Mode: If the user's system is set to light mode, it gracefully falls back to a warm parchment palette.

## Customization

Override the CSS variables to change the theme:

```css
:root {
  --night-bg: #16130f;
  --night-fg: #c9bfb2;
  --night-accent: #8fb3d9;
}
```
