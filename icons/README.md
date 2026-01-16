# Icons

This folder contains **icons and iconsets** for use in plugins, mods, websites, and user interfaces.

## 📋 Purpose

The `icons/` folder is designated for:
- UI icons (buttons, navigation, actions, etc.)
- Plugin/mod icon assets
- Application and feature icons
- Icon families and collections
- Icon variations (sizes, styles, states)

## 📝 Naming Conventions

Use **lowercase letters and hyphens** for all filenames:

```
plugin-icon.svg
settings-gear.png
user-profile-24px.svg
close-button-dark.png
achievement-badge.svg
```

**Format:** `[icon-name]-[variant].[extension]`

- `icon-name`: descriptive, lowercase, hyphens between words
- `variant`: optional, describes size or style (e.g., 16px, 24px, 32px, dark, light)
- `extension`: file format

## ✅ Supported Formats

| Format | Use Case | Priority |
|--------|----------|----------|
| **SVG** | Scalable icons, web/UI use, preferred | ⭐⭐⭐ High |
| **PNG** | Fixed sizes, web/app use, fallback | ⭐⭐⭐ High |
| **GIF** | Animated icons, special effects | ⭐⭐ Medium |
| **JPG/JPEG** | Raster icons (rare) | ⭐ Low |

## 📤 Upload Rules

1. **Prefer SVG for primary icons** (scale to any size without quality loss)
2. **Provide PNG versions** for common sizes (16px, 24px, 32px, 64px)
3. **Use transparent backgrounds** (PNG with alpha channel)
4. **Consistent stroke width** and padding across icon sets
5. **Organize by category** if submitting large collections:
   - `icons/ui-controls/` – buttons, toggles, inputs
   - `icons/navigation/` – menus, arrows, tabs
   - `icons/actions/` – play, pause, download, etc.
   - `icons/social/` – social media icons
6. **Include size specifications** in filename or documentation
7. **Maintain consistent style:**
   - Line weight/stroke width
   - Corner radius (if applicable)
   - Padding and alignment
   - Color palette alignment

## 📦 Examples

```
icons/
├── plugin-icon.svg                     # Main plugin icon
├── plugin-icon-16px.png
├── plugin-icon-24px.png
├── plugin-icon-32px.png
├── plugin-icon-64px.png
├── settings-icon.svg
├── settings-icon-dark.png              # Dark variant
├── ui-controls/
│   ├── button-primary.svg
│   ├── button-secondary.svg
│   ├── toggle-on.svg
│   └── toggle-off.svg
├── navigation/
│   ├── arrow-left.svg
│   ├── arrow-right.svg
│   ├── menu.svg
│   └── close.svg
└── actions/
    ├── download.svg
    ├── upload.svg
    ├── delete.svg
    └── share.svg
```

## 🎨 Design Guidelines

- **Standard sizes:** 16x16, 24x24, 32x32, 48x48, 64x64, 128x128px
- **Line weight:** Consistent across all icons in a set (typically 1.5-2px)
- **Padding:** Maintain consistent internal padding
- **Grid-based:** Design on a pixel grid for crisp appearance
- **Alignment:** Center content within the canvas
- **Color:** Use single color or 2-3 colors maximum; ensure contrast
- **Accessibility:** High contrast for visibility, avoid color-only differentiation

## 🏷️ Common Icon Categories

| Category | Examples |
|----------|----------|
| **Navigation** | Home, back, forward, menu, close, settings |
| **Actions** | Add, delete, edit, download, upload, share, search |
| **Status** | Success, error, warning, info, loading, notification |
| **Media** | Play, pause, stop, next, previous, mute, volume |
| **UI Controls** | Button, checkbox, radio, toggle, slider, dropdown |
| **Social** | Facebook, Twitter, Discord, GitHub, YouTube |

## 📞 Questions?

Refer to the main [README.md](../README.md) for repository guidelines or contact the Myzon team.
