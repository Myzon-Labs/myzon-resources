# Myzon Resources

A centralized repository for storing Myzon media, images, and visual assets. This repository serves as the single source of truth for all Myzon branding materials, icons, screenshots, and promotional content.

## 📁 Repository Structure

```
myzon-resources/
├── logos/          # Company and product logos
├── icons/          # UI icons and small graphics
├── screenshots/    # Application screenshots and UI captures
├── banners/        # Marketing banners and hero images
└── README.md       # This file
```

## 📋 Purpose

This repository is designed to:
- **Centralize** all Myzon visual assets in one accessible location
- **Version control** changes to branding and media files
- **Facilitate collaboration** between design, marketing, and development teams
- **Ensure consistency** across all Myzon products and platforms
- **Provide easy access** to approved assets for all team members

## 📤 Upload Instructions

### Prerequisites
- Git installed on your local machine
- Write access to this repository
- Assets reviewed and approved by the design team

### Steps to Upload

1. **Clone the repository** (if you haven't already):
   ```bash
   git clone https://github.com/Myzon-Labs/myzon-resources.git
   cd myzon-resources
   ```

2. **Create a new branch** for your changes:
   ```bash
   git checkout -b add-new-assets
   ```

3. **Add your files** to the appropriate folder:
   ```bash
   # Example: adding a logo
   cp /path/to/your/logo.png logos/
   ```

4. **Commit your changes** with a descriptive message:
   ```bash
   git add .
   git commit -m "Add: New Myzon product logo variants"
   ```

5. **Push your branch** to the repository:
   ```bash
   git push origin add-new-assets
   ```

6. **Create a Pull Request** on GitHub for review

### Quick Upload via GitHub Web Interface
1. Navigate to the appropriate folder on GitHub
2. Click "Add file" > "Upload files"
3. Drag and drop your files or click to browse
4. Add a descriptive commit message
5. Create a pull request or commit directly (if you have permissions)

## 🏷️ Naming Conventions

Follow these naming conventions to maintain consistency and make assets easy to find:

### General Rules
- Use **lowercase letters** only
- Use **hyphens** (`-`) to separate words (no spaces or underscores)
- Include **descriptive names** that clearly identify the asset
- Add **version numbers** when applicable (e.g., `v1`, `v2`)
- Include **dimensions** for size-specific variants (e.g., `512x512`, `1920x1080`)

### Format by Category

#### Logos (`logos/`)
```
myzon-logo-primary.svg
myzon-logo-white.svg
myzon-logo-black.svg
myzon-logo-icon-only.png
myzon-wordmark-horizontal.svg
myzon-wordmark-vertical.svg
product-name-logo-v2.svg
```

#### Icons (`icons/`)
```
icon-name-action.svg
icon-name-state-size.png
icon-home-24x24.svg
icon-settings-filled-32x32.png
icon-user-outline.svg
```

#### Screenshots (`screenshots/`)
```
app-name-feature-description.png
dashboard-main-view-2024-01-15.png
mobile-login-screen-ios.png
web-checkout-flow-step1.png
```

#### Banners (`banners/`)
```
campaign-name-platform-size.jpg
hero-homepage-1920x600.png
social-media-facebook-cover.jpg
email-header-announcement.png
```

### Examples
✅ **Good:**
- `myzon-logo-primary.svg`
- `icon-search-24x24.svg`
- `dashboard-analytics-view.png`
- `hero-homepage-1920x600.jpg`

❌ **Bad:**
- `Logo.svg` (not descriptive)
- `icon_search.svg` (uses underscore)
- `Screenshot 2024.png` (not descriptive)
- `BANNER.JPG` (uppercase)

## 🎨 Recommended Formats

### Logos
- **Primary format:** SVG (scalable, best for logos)
- **Alternative:** PNG with transparent background
- **Minimum resolution (if PNG):** 1024x1024px
- **Color modes:** Provide full color, white, and black versions

### Icons
- **Primary format:** SVG (scalable, small file size)
- **Alternative:** PNG with transparent background
- **Common sizes:** 16x16, 24x24, 32x32, 48x48, 64x64, 128x128, 256x256, 512x512
- **Style:** Consistent stroke width and corner radius

### Screenshots
- **Format:** PNG (lossless quality for UI elements)
- **Alternative:** JPG (for photographs or large images)
- **Resolution:** Original screen resolution (e.g., 1920x1080, 2560x1440)
- **Compression:** Optimize file size while maintaining clarity
- **Include:** Realistic data when possible (avoid lorem ipsum)

### Banners
- **Format:** JPG (good compression for large images)
- **Alternative:** PNG (if transparency is needed)
- **Common sizes:**
  - Web hero: 1920x600 to 1920x1080
  - Social media: Platform-specific (e.g., 820x312 for Twitter)
  - Email: 600x200 to 600x400
- **Optimization:** Compress to reasonable file size (aim for <500KB)

## 🔍 File Size Guidelines

To keep the repository manageable:
- **Logos:** < 1MB (preferably < 200KB)
- **Icons:** < 100KB
- **Screenshots:** < 2MB (compress if larger)
- **Banners:** < 1MB (optimize for web)

Use tools like [TinyPNG](https://tinypng.com/), [SVGOMG](https://jakearchibald.github.io/svgomg/), or [ImageOptim](https://imageoptim.com/) to optimize files before uploading.

## 🎯 Best Practices

1. **Version Control:** Keep old versions by renaming (e.g., `logo-v1.svg`, `logo-v2.svg`) rather than deleting
2. **Documentation:** Update this README when adding new categories or changing conventions
3. **Review Process:** All assets should be reviewed by the design team before merging
4. **Organize:** Keep files organized in the correct folders
5. **Optimize:** Always optimize files before uploading to reduce repository size
6. **Backup:** Keep original, uncompressed versions in a separate backup location

## 📝 Usage Examples

### In Markdown/Documentation
```markdown
![Myzon Logo](https://raw.githubusercontent.com/Myzon-Labs/myzon-resources/main/logos/myzon-logo-primary.svg)
```

### In HTML
```html
<img src="https://raw.githubusercontent.com/Myzon-Labs/myzon-resources/main/logos/myzon-logo-primary.svg" alt="Myzon Logo" width="200">
```

### In Web Applications
```javascript
const logoUrl = 'https://raw.githubusercontent.com/Myzon-Labs/myzon-resources/main/logos/myzon-logo-primary.svg';
```

## 🤝 Contributing

To contribute new assets or improvements:
1. Fork this repository
2. Create a feature branch
3. Add your assets following the guidelines above
4. Submit a pull request with a clear description
5. Wait for review from the design team

## 📞 Support

For questions or assistance:
- Open an issue in this repository
- Contact the design team
- Review the guidelines in this README

## 📄 License

All assets in this repository are licensed under [CC0 1.0 Universal](LICENSE) unless otherwise specified.
