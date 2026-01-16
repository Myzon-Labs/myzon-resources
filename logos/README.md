# Logos

This folder contains official **Myzon logos** and branding assets for use across plugins, mods, websites, and marketing materials.

## 📋 Purpose

The `logos/` folder is designated for:
- Official Myzon brand logos
- Company/project branding assets
- Logos for different use cases (horizontal, vertical, square, etc.)
- Variations (dark mode, light mode, monochrome, etc.)

## 📝 Naming Conventions

Use **lowercase letters and hyphens** for all filenames:

```
myzon-logo-horizontal.svg
myzon-logo-vertical-dark.png
myzon-logo-white-bg.svg
myzon-wordmark.png
myzon-icon-badge.png
```

**Format:** `[project-name]-[variant-description].[extension]`

- `project-name`: lowercase, hyphens between words
- `variant-description`: optional, describes the variant (dark, light, horizontal, vertical, etc.)
- `extension`: file format

## ✅ Supported Formats

| Format | Use Case | Priority |
|--------|----------|----------|
| **SVG** | Scalable logos, web use, preferred format | ⭐⭐⭐ High |
| **PNG** | Transparent backgrounds, web/app use | ⭐⭐⭐ High |
| **JPG/JPEG** | Backgrounds, full-color logos | ⭐⭐ Medium |
| **GIF** | Animations, special effects | ⭐ Low |

## 📤 Upload Rules

1. **Always provide SVG versions** when possible (scalable and versatile)
2. **Include PNG versions** with transparent backgrounds
3. **Use descriptive filenames** that indicate variant/purpose
4. **Organize by type:**
   - Primary logos in root of folder
   - Variants in subfolders if needed (e.g., `logos/dark-mode/`, `logos/monochrome/`)
5. **Include documentation** in a comment or separate file for complex logo suites
6. **Maintain quality:**
   - Minimum 200x200px for small logos
   - Minimum 1000x1000px for primary/large logos
   - Avoid compression artifacts

## 📦 Examples

```
logos/
├── myzon-logo-primary.svg              # Main logo
├── myzon-logo-primary.png              # PNG version with transparency
├── myzon-logo-horizontal.svg           # Horizontal variant
├── myzon-logo-vertical.svg             # Vertical variant
├── myzon-logo-white.png                # White variant for dark backgrounds
├── myzon-logo-dark.png                 # Dark variant for light backgrounds
├── myzon-icon-badge.svg                # Simplified icon badge
└── dark-mode/
    ├── myzon-logo-dark-mode.svg
    └── myzon-logo-dark-mode.png
```

## 🎨 Design Guidelines

- Maintain aspect ratio consistency
- Use official Myzon color palette
- Ensure legibility at small sizes
- Test on both light and dark backgrounds
- Preserve proper spacing/padding around logo

## 📞 Questions?

Refer to the main [README.md](../README.md) for repository guidelines or contact the Myzon team.
