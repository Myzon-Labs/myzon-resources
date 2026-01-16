# Placeholders

This folder contains **sample and placeholder images** for development, testing, and temporary use across Myzon projects.

## 📋 Purpose

The `placeholders/` folder is designated for:
- Temporary/example images during development
- Placeholder graphics for UI mockups
- Test images for features (avatar, thumbnail, hero, etc.)
- Sample assets for documentation
- Fallback images for error states
- Development and QA testing assets

## 📝 Naming Conventions

Use **lowercase letters and hyphens** for all filenames:

```
placeholder-avatar-user.png
placeholder-thumbnail-video.jpg
placeholder-hero-image-1920x500.png
sample-profile-picture.png
test-image-1024x1024.svg
```

**Format:** `placeholder-[type]-[description].[extension]`

- `placeholder`: prefix for clarity (optional but recommended)
- `type`: what it represents (avatar, thumbnail, hero, profile, etc.)
- `description`: optional, additional context
- `extension`: file format

## ✅ Supported Formats

| Format | Use Case | Priority |
|--------|----------|----------|
| **PNG** | Transparent backgrounds, quality | ⭐⭐⭐ High |
| **JPG/JPEG** | Full-color, photos, smaller files | ⭐⭐⭐ High |
| **SVG** | Scalable placeholders, simple graphics | ⭐⭐ Medium |
| **GIF** | Animated placeholders, demonstrations | ⭐ Low |

## 📤 Upload Rules

1. **Clearly mark as placeholder:**
   - Use "placeholder-" prefix in filename
   - Include watermark or label if appropriate (e.g., "SAMPLE")
2. **Include multiple sizes:**
   - Small (128x128px for thumbnails)
   - Medium (512x512px for profiles)
   - Large (1024x1024px or greater for full displays)
3. **Document intended use:**
   - Avatar placeholders with standard sizes (64x64, 128x128, 256x256px)
   - Thumbnail placeholders (240x240, 360x360px)
   - Hero/banner placeholders (matching banner dimensions)
4. **Use neutral, generic content:**
   - No copyrighted material
   - No personal information
   - Professional appearance for screenshots/demos
5. **Version control:**
   - Keep sample files minimal to reduce repo size
   - Remove obsolete placeholders periodically
6. **Organization:**
   - Group related sizes together (avatar series, thumbnail series, etc.)
   - Include subfolders for major categories if many images

## 📦 Examples

```
placeholders/
├── placeholder-avatar-default-128x128.png
├── placeholder-avatar-default-256x256.png
├── placeholder-avatar-default-512x512.png
├── placeholder-thumbnail-video-240x240.png
├── placeholder-thumbnail-video-360x360.png
├── placeholder-thumbnail-image-400x300.jpg
├── placeholder-hero-1920x500.png
├── placeholder-user-profile-picture-200x200.png
├── sample-product-image-1024x1024.jpg
├── sample-banner-gradient-1200x600.png
├── avatars/
│   ├── avatar-user-01-256x256.png
│   ├── avatar-user-02-256x256.png
│   └── avatar-bot-256x256.png
├── thumbnails/
│   ├── video-thumbnail-360x360.jpg
│   ├── image-thumbnail-300x300.jpg
│   └── article-thumbnail-400x300.png
└── ui-components/
    ├── loading-spinner.svg
    ├── error-image.png
    └── no-results-icon.svg
```

## 📏 Standard Placeholder Sizes

| Use Case | Dimensions | Aspect Ratio |
|----------|-----------|-------------|
| **Avatar (Small)** | 64x64px | 1:1 |
| **Avatar (Medium)** | 128x128px | 1:1 |
| **Avatar (Large)** | 256x256px | 1:1 |
| **Profile Picture** | 200x200px | 1:1 |
| **Thumbnail (Small)** | 240x240px | 1:1 |
| **Thumbnail (Medium)** | 360x360px | 1:1 |
| **Thumbnail (Video)** | 320x180px | 16:9 |
| **Card Image** | 400x300px | 4:3 |
| **Hero Image** | 1920x500px | 16:6.5 |

## 🎨 Design Guidelines

- **Universal appeal:** Use generic/neutral visuals
- **Professional quality:** Even placeholders should look polished
- **Consistency:** Match Myzon brand colors and style where appropriate
- **Contrast:** Ensure readability and visibility
- **Legibility:** Add text labels if needed (e.g., size dimensions)
- **Accessibility:** Use high-contrast colors; avoid color-only information

## 📋 Sample Content Ideas

| Type | Suggestions |
|------|------------|
| **Avatars** | Silhouettes, geometric patterns, initials, gradient backgrounds |
| **Thumbnails** | Color gradients, geometric shapes, simple icons |
| **Hero Images** | Abstract designs, brand colors, minimal text overlays |
| **Cards** | Simple backgrounds with text hierarchy |
| **Icons** | Simplified symbols, material design style |

## ⚠️ Important Notes

- **Replace before production:** Always replace placeholders with real content before shipping
- **Temporary use only:** These are not intended for permanent production deployment
- **Clean up:** Remove outdated placeholders to keep repository lightweight
- **Documentation:** Update this README when adding major new placeholder series

## 📞 Questions?

Refer to the main [README.md](../README.md) for repository guidelines or contact the Myzon team.
