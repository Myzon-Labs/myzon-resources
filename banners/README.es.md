# Banners

Esta carpeta contiene **banners promocionales y de encabezado** para sitios web, plugins, mods y materiales de marketing.

## 📋 Propósito

La carpeta `banners/` está designada para:
- Banners de encabezado/héroe de sitio web
- Banners promocionales para campañas
- Banners de características de plugin/mod
- Banners de redes sociales
- Banners de anuncio de lanzamiento
- Elementos visuales de página de destino

## 📝 Convenciones de Nombres

Usa **letras minúsculas y guiones** para todos los nombres de archivo:

```
myzon-hero-banner-homepage.svg
plugin-feature-announcement.png
summer-campaign-banner.jpg
release-v1.0-promotional.png
social-media-banner-1200x630.png
```

**Formato:** `[propósito]-[tipo]-[variante].[extensión]`

- `propósito`: para qué es (myzon, plugin-name, campaign-name)
- `tipo`: tipo de banner (hero, announcement, campaign, social)
- `variante`: opcional, describe contexto o tamaño
- `extensión`: formato de archivo

## ✅ Formatos Soportados

| Formato | Caso de Uso | Prioridad |
|---------|-----------|-----------|
| **SVG** | Banners escalables, preferido para web | ⭐⭐⭐ Alto |
| **PNG** | Fondos transparentes, uso en web | ⭐⭐⭐ Alto |
| **JPG/JPEG** | Imágenes a todo color, fotos | ⭐⭐⭐ Alto |
| **GIF** | Banners animados, promociones | ⭐⭐ Medio |

## 📤 Reglas de Carga

1. **Proporciona versiones SVG** cuando sea posible (escalable para cualquier pantalla)
2. **Incluye alternativas PNG** para compatibilidad con navegadores antiguos
3. **Optimiza para web:**
   - Usa SVG optimizado para CSS
   - Comprime JPG/PNG (mantén menos de 500KB por archivo)
   - Prueba tamaño de archivo en diferentes conexiones
4. **Incluye múltiples tamaños:**
   - Escritorio (1920x400px, 1920x500px)
   - Tableta (1024x300px)
   - Móvil (400x300px, variantes a ancho completo)
5. **Añade metadatos:**
   - Incluye especificaciones de dimensión en nombre o documentación
   - Nota el uso previsto (sitio web, social, email, etc.)
6. **Consideraciones de diseño:**
   - Responsivo: Funciona en todos los tamaños de pantalla
   - Zona de texto segura: Mantén texto lejos de bordes (área segura: centro 80%)
   - Contraste: Asegura que el texto sea legible sobre el fondo
7. **Organiza por campaña/propósito:**
   - Nivel raíz para banners permanentes
   - Subcarpetas para campañas estacionales o series

## 📦 Ejemplos

```
banners/
├── myzon-hero-homepage.svg             # Hero principal del sitio web
├── myzon-hero-homepage-1920x500.png    # Alternativa PNG
├── plugin-feature-announcement.png     # Promoción de plugin
├── release-v1.0-banner.svg             # Anuncio de lanzamiento
├── release-v1.0-banner-1920x400.jpg    # Alternativa JPG
├── social-media/
│   ├── twitter-banner-1500x500.png     # Encabezado de Twitter
│   ├── discord-banner-960x540.png      # Banner de servidor Discord
│   ├── youtube-banner-2560x1440.png    # Banner de canal YouTube
│   └── og-image-1200x630.png           # Imagen Open Graph
├── seasonal-campaigns/
│   ├── winter-2025-banner.png
│   ├── new-year-promotion.svg
│   └── event-announcement.png
└── email-banners/
    ├── newsletter-header-600x200.png
    └── promotional-footer-600x300.png
```

## 📏 Dimensiones Recomendadas

| Plataforma/Uso | Dimensiones | Relación de Aspecto |
|----------------|-----------|-------------------|
| **Hero del Sitio Web** | 1920x500px | 16:6.5 |
| **Hero del Sitio Web (Móvil)** | 400x300px | 4:3 |
| **Encabezado de Twitter** | 1500x500px | 3:1 |
| **Servidor Discord** | 960x540px | 16:9 |
| **Canal YouTube** | 2560x1440px | 16:9 |
| **Portada de Facebook** | 820x312px | 2.62:1 |
| **Banner de LinkedIn** | 1200x627px | 1.91:1 |
| **Encabezado de Email** | 600x200px | 3:1 |
| **Open Graph (Social)** | 1200x630px | 1.91:1 |

## 🎨 Directrices de Diseño

- **Legibilidad de texto:** Usa alto contraste, legible en tamaño miniatura
- **Zona segura:** Mantén contenido importante en centro 80% (evita bordes)
- **Responsivo para móvil:** Diseña primero para móvil, escala hacia arriba
- **Marca:** Consistente con directrices de marca de Myzon
- **Legibilidad:** Prueba en fondos claros y oscuros
- **Carga:** Optimiza tamaño de archivo para carga rápida (< 500KB)
- **Accesibilidad:** Incluye texto alt en HTML; asegura suficiente contraste de color

## 📋 Directrices de Contenido

| Tipo de Banner | Contenido Típico | Duración |
|----------------|-----------------|----------|
| **Banner Hero** | Mensaje principal, botón CTA | Permanente |
| **Anuncio** | Resaltado de característica/lanzamiento | 2-4 semanas |
| **Campaña** | Mensaje promocional, oferta | Duración de la campaña |
| **Estacional** | Temática de vacaciones/evento | Específico de temporada |
| **Red Social** | Visual atractivo, texto mínimo | Varía por plataforma |

## 📞 ¿Preguntas?

Consulta el [README.md](../README.md) principal para directrices del repositorio o contacta al equipo de Myzon.
