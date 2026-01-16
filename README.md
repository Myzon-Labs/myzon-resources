# Myzon Resources

A centralized repository for storing Myzon media, images, and visual assets. This repository serves as the single source of truth for all Myzon branding materials, screenshots, and promotional content.

## 📁 Folder Structure

```
myzon-resources/
├── logos/          # Company and product logos
├── icons/          # App icons, favicons, and UI icons
├── screenshots/    # Application and product screenshots
└── banners/        # Marketing banners and hero images
```

### Logos
Contains official Myzon logos in various formats and variations:
- Full color logos
- Monochrome versions
- Logo variations with taglines
- Transparent backgrounds for overlays

### Icons
Application icons, favicons, and UI elements:
- App icons for different platforms (iOS, Android, Web)
- Favicons in multiple sizes
- Social media icons
- UI icon sets

### Screenshots
Product and application screenshots:
- Desktop application screenshots
- Mobile app screenshots
- Feature highlights
- User interface examples

### Banners
Marketing and promotional banner images:
- Website hero images
- Social media banners
- Event banners
- Promotional graphics

## 📤 Upload Instructions

### Before Uploading
1. **Review Naming Conventions**: Ensure your file follows the naming conventions outlined below
2. **Check Format**: Verify your file is in one of the recommended formats
3. **Optimize File Size**: Compress images appropriately without sacrificing quality
4. **Review Content**: Ensure no sensitive information is visible in screenshots

### How to Upload
1. Clone the repository:
   ```bash
   git clone https://github.com/Myzon-Labs/myzon-resources.git
   cd myzon-resources
   ```

2. Create a new branch:
   ```bash
   git checkout -b add-new-assets
   ```

3. Add your files to the appropriate folder:
   ```bash
   cp /path/to/your/file.png logos/
   ```

4. Commit and push your changes:
   ```bash
   git add .
   git commit -m "Add: [brief description of assets]"
   git push origin add-new-assets
   ```

5. Create a Pull Request on GitHub for review

## 📝 Naming Conventions

Follow these naming conventions to maintain consistency:

### General Rules
- Use lowercase letters
- Separate words with hyphens (`-`)
- Be descriptive but concise
- Include dimensions when relevant
- Include version or date for iterations

### Format Examples

**Logos:**
```
myzon-logo-primary.svg
myzon-logo-white.png
myzon-logo-icon-only.svg
myzon-wordmark-horizontal.png
```

**Icons:**
```
app-icon-ios-1024x1024.png
favicon-32x32.png
icon-profile-user.svg
social-icon-twitter.png
```

**Screenshots:**
```
dashboard-desktop-main-1920x1080.png
mobile-app-login-screen-750x1334.png
feature-analytics-overview.png
screenshot-checkout-flow-2024-01.png
```

**Banners:**
```
hero-banner-homepage-1920x600.jpg
social-banner-twitter-1200x628.png
event-banner-launch-2024.png
promo-banner-seasonal-sale.jpg
```

## 🎨 Recommended Formats

### File Formats by Category

| Asset Type | Preferred Formats | Use Case |
|------------|------------------|----------|
| **Logos** | SVG, PNG (with transparency) | Scalable vector for print and web |
| **Icons** | SVG, PNG | UI elements and app icons |
| **Screenshots** | PNG, JPG | Product documentation and marketing |
| **Banners** | JPG, PNG, WebP | Web and social media |

### Format Guidelines

**SVG (Scalable Vector Graphics)**
- ✅ Best for: Logos, icons, simple graphics
- ✅ Advantages: Infinitely scalable, small file size
- ❌ Not ideal for: Photographs, complex images

**PNG (Portable Network Graphics)**
- ✅ Best for: Logos with transparency, screenshots, UI elements
- ✅ Advantages: Lossless compression, supports transparency
- ⚠️ Note: Larger file size than JPG

**JPG/JPEG (Joint Photographic Experts Group)**
- ✅ Best for: Photographs, complex images, banners
- ✅ Advantages: Small file size, widely supported
- ❌ Limitations: No transparency, lossy compression

**WebP**
- ✅ Best for: Web-optimized images
- ✅ Advantages: Superior compression, supports transparency
- ⚠️ Note: Limited support in older browsers

### Recommended Dimensions

**Logos:**
- SVG: Vector (scalable)
- PNG: 512x512px (square), 1000xAuto (horizontal)

**Icons:**
- App Icons: 1024x1024px (will be scaled down)
- Favicons: 32x32px, 64x64px, 180x180px
- Social Icons: 512x512px

**Screenshots:**
- Desktop: 1920x1080px, 2560x1440px
- Mobile: 750x1334px (iPhone), 1080x1920px (Android)
- Tablet: 1536x2048px

**Banners:**
- Hero Banners: 1920x600px, 2560x800px
- Social Media:
  - Twitter/X: 1200x675px
  - Facebook: 1200x630px
  - LinkedIn: 1200x627px
  - Instagram: 1080x1080px (square), 1080x1350px (portrait)

## 🔍 Finding Assets

### Browse by Folder
Navigate to the appropriate folder to view all assets of that type.

### Search by Name
Use GitHub's search feature to find specific assets by name or description.

### Using Assets in Projects
To reference assets in your projects, use the raw GitHub URL:
```
https://raw.githubusercontent.com/Myzon-Labs/myzon-resources/main/logos/myzon-logo-primary.svg
```

Or clone the repository and reference locally:
```bash
git clone https://github.com/Myzon-Labs/myzon-resources.git
```

## 📋 Best Practices

1. **Version Control**: Keep old versions by appending version numbers or dates
2. **Optimization**: Always optimize images before uploading
3. **Documentation**: Update this README if adding new categories
4. **Licensing**: Ensure all uploaded assets have proper rights and permissions
5. **Quality**: Maintain high-quality assets suitable for professional use
6. **Consistency**: Follow brand guidelines for all visual assets
7. **Backups**: This repository serves as a backup, but maintain local copies

## 🤝 Contributing

We welcome contributions! Please:
1. Follow the naming conventions
2. Use recommended formats and dimensions
3. Create a pull request with a clear description
4. Ensure assets are properly optimized
5. Verify no sensitive information is included

## 📄 License

This repository is licensed under CC0 1.0 Universal (Public Domain). All assets are free to use, modify, and distribute without restriction. See [LICENSE](LICENSE) for details.

## 📞 Contact

For questions or access requests, please contact the Myzon Labs team or open an issue in this repository.

---

**Last Updated:** January 2026
