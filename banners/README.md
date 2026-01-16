# Banners

This folder contains **promotional and header banners** for websites, plugins, mods, and marketing materials.

## 📋 Purpose

The `banners/` folder is designated for:
- Website header/hero banners
- Promotional banners for campaigns
- Plugin/mod feature banners
- Social media banners
- Release announcement banners
- Landing page visuals

## 📝 Naming Conventions

Use **lowercase letters and hyphens** for all filenames:

```
myzon-hero-banner-homepage.svg
plugin-feature-announcement.png
summer-campaign-banner.jpg
release-v1.0-promotional.png
social-media-banner-1200x630.png
```

**Format:** `[purpose]-[type]-[variant].[extension]`

- `purpose`: what it's for (myzon, plugin-name, campaign-name)
- `type`: banner type (hero, announcement, campaign, social)
- `variant`: optional, describes context or size
- `extension`: file format

## ✅ Supported Formats

| Format | Use Case | Priority |
|--------|----------|----------|
| **SVG** | Scalable banners, preferred for web | ⭐⭐⭐ High |
| **PNG** | Transparent backgrounds, web use | ⭐⭐⭐ High |
| **JPG/JPEG** | Full-color images, photos | ⭐⭐⭐ High |
| **GIF** | Animated banners, promotions | ⭐⭐ Medium |

## 📤 Upload Rules

1. **Provide SVG versions** when possible (scalable for any screen)
2. **Include PNG fallbacks** for older browser compatibility
3. **Optimize for web:**
   - Use CSS-optimized SVG
   - Compress JPG/PNG (keep under 500KB per file)
   - Test file size on different connections
4. **Include multiple sizes:**
   - Desktop (1920x400px, 1920x500px)
   - Tablet (1024x300px)
   - Mobile (400x300px, full-width variants)
5. **Add metadata:**
   - Include dimension specs in filename or documentation
   - Note intended use (website, social, email, etc.)
6. **Design considerations:**
   - Responsive: Works on all screen sizes
   - Safe text zone: Keep text away from edges (safe area: center 80%)
   - Contrast: Ensure text is readable over background
7. **Organize by campaign/purpose:**
   - Root level for permanent banners
   - Subfolders for seasonal campaigns or series

## 📦 Examples

```
banners/
├── myzon-hero-homepage.svg             # Main website hero
├── myzon-hero-homepage-1920x500.png    # PNG fallback
├── plugin-feature-announcement.png     # Plugin promotion
├── release-v1.0-banner.svg             # Release announcement
├── release-v1.0-banner-1920x400.jpg    # JPG alternative
├── social-media/
│   ├── twitter-banner-1500x500.png     # Twitter header
│   ├── discord-banner-960x540.png      # Discord server banner
│   ├── youtube-banner-2560x1440.png    # YouTube channel banner
│   └── og-image-1200x630.png           # Open Graph image
├── seasonal-campaigns/
│   ├── winter-2025-banner.png
│   ├── new-year-promotion.svg
│   └── event-announcement.png
└── email-banners/
    ├── newsletter-header-600x200.png
    └── promotional-footer-600x300.png
```

## 📏 Recommended Dimensions

| Platform/Use | Dimensions | Aspect Ratio |
|--------------|-----------|-------------|
| **Website Hero** | 1920x500px | 16:6.5 |
| **Website Hero (Mobile)** | 400x300px | 4:3 |
| **Twitter Header** | 1500x500px | 3:1 |
| **Discord Server** | 960x540px | 16:9 |
| **YouTube Channel** | 2560x1440px | 16:9 |
| **Facebook Cover** | 820x312px | 2.62:1 |
| **LinkedIn Banner** | 1200x627px | 1.91:1 |
| **Email Header** | 600x200px | 3:1 |
| **Open Graph (Social)** | 1200x630px | 1.91:1 |

## 🎨 Design Guidelines

- **Text legibility:** Use high contrast, readable at thumbnail size
- **Safe zone:** Keep important content in center 80% (avoid edges)
- **Mobile responsive:** Design for mobile-first, scale up
- **Branding:** Consistent with Myzon brand guidelines
- **Readability:** Test on both light and dark backgrounds
- **Loading:** Optimize file size for fast loading (< 500KB)
- **Accessibility:** Include alt text in HTML; ensure sufficient color contrast

## 📋 Content Guidelines

| Banner Type | Typical Content | Duration |
|------------|-----------------|----------|
| **Hero Banner** | Main message, CTA button | Permanent |
| **Announcement** | Feature/release highlight | 2-4 weeks |
| **Campaign** | Promotional message, offer | Campaign duration |
| **Seasonal** | Holiday/event themed | Season-specific |
| **Social Media** | Engaging visual, minimal text | Varies by platform |

## 📞 Questions?

Refer to the main [README.md](../README.md) for repository guidelines or contact the Myzon team.
