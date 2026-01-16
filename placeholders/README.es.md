# Marcadores de Posición

Esta carpeta contiene **imágenes de muestra y marcadores de posición** para desarrollo, pruebas y uso temporal en proyectos de Myzon.

## 📋 Propósito

La carpeta `placeholders/` está designada para:
- Imágenes temporales/de ejemplo durante el desarrollo
- Gráficos de marcador de posición para maquetas de UI
- Imágenes de prueba para características (avatar, miniatura, héroe, etc.)
- Activos de muestra para documentación
- Imágenes alternativas para estados de error
- Activos de desarrollo y pruebas de QA

## 📝 Convenciones de Nombres

Usa **letras minúsculas y guiones** para todos los nombres de archivo:

```
placeholder-avatar-user.png
placeholder-thumbnail-video.jpg
placeholder-hero-image-1920x500.png
sample-profile-picture.png
test-image-1024x1024.svg
```

**Formato:** `placeholder-[tipo]-[descripción].[extensión]`

- `placeholder`: prefijo para claridad (opcional pero recomendado)
- `tipo`: qué representa (avatar, thumbnail, hero, profile, etc.)
- `descripción`: opcional, contexto adicional
- `extensión`: formato de archivo

## ✅ Formatos Soportados

| Formato | Caso de Uso | Prioridad |
|---------|-----------|-----------|
| **PNG** | Fondos transparentes, calidad | ⭐⭐⭐ Alto |
| **JPG/JPEG** | A todo color, fotos, archivos más pequeños | ⭐⭐⭐ Alto |
| **SVG** | Marcadores de posición escalables, gráficos simples | ⭐⭐ Medio |
| **GIF** | Marcadores de posición animados, demostraciones | ⭐ Bajo |

## 📤 Reglas de Carga

1. **Marca claramente como marcador de posición:**
   - Usa prefijo "placeholder-" en el nombre de archivo
   - Incluye marca de agua o etiqueta si es apropiado (ej: "SAMPLE")
2. **Incluye múltiples tamaños:**
   - Pequeño (128x128px para miniaturas)
   - Medio (512x512px para perfiles)
   - Grande (1024x1024px o mayor para visualizaciones completas)
3. **Documenta el uso previsto:**
   - Marcadores de posición de avatar con tamaños estándar (64x64, 128x128, 256x256px)
   - Marcadores de posición de miniatura (240x240, 360x360px)
   - Marcadores de posición de héroe/banner (que coincidan con dimensiones de banner)
4. **Usa contenido neutral y genérico:**
   - Sin material con derechos de autor
   - Sin información personal
   - Apariencia profesional para capturas de pantalla/demos
5. **Control de versión:**
   - Mantén archivos de muestra mínimos para reducir tamaño de repositorio
   - Elimina marcadores de posición obsoletos periódicamente
6. **Organización:**
   - Agrupa tamaños relacionados juntos (serie de avatares, serie de miniaturas, etc.)
   - Incluye subcarpetas para categorías principales si hay muchas imágenes

## 📦 Ejemplos

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

## 📏 Tamaños Estándar de Marcadores de Posición

| Caso de Uso | Dimensiones | Relación de Aspecto |
|-------------|-----------|-------------------|
| **Avatar (Pequeño)** | 64x64px | 1:1 |
| **Avatar (Medio)** | 128x128px | 1:1 |
| **Avatar (Grande)** | 256x256px | 1:1 |
| **Foto de Perfil** | 200x200px | 1:1 |
| **Miniatura (Pequeña)** | 240x240px | 1:1 |
| **Miniatura (Media)** | 360x360px | 1:1 |
| **Miniatura (Video)** | 320x180px | 16:9 |
| **Imagen de Tarjeta** | 400x300px | 4:3 |
| **Imagen Hero** | 1920x500px | 16:6.5 |

## 🎨 Directrices de Diseño

- **Atractivo universal:** Usa elementos visuales genéricos/neutrales
- **Calidad profesional:** Incluso los marcadores de posición deben verse pulidos
- **Consistencia:** Coincide con colores de marca y estilo de Myzon donde sea apropiado
- **Contraste:** Asegura legibilidad y visibilidad
- **Legibilidad:** Añade etiquetas de texto si es necesario (ej: dimensiones de tamaño)
- **Accesibilidad:** Usa colores de alto contraste; evita diferenciación solo por color

## 📋 Ideas de Contenido de Muestra

| Tipo | Sugerencias |
|------|-----------|
| **Avatares** | Siluetas, patrones geométricos, iniciales, fondos de gradiente |
| **Miniaturas** | Gradientes de color, formas geométricas, iconos simples |
| **Imágenes Hero** | Diseños abstractos, colores de marca, superposiciones de texto mínimo |
| **Tarjetas** | Fondos simples con jerarquía de texto |
| **Iconos** | Símbolos simplificados, estilo material design |

## ⚠️ Notas Importantes

- **Reemplaza antes de producción:** Siempre reemplaza marcadores de posición con contenido real antes de enviar
- **Solo uso temporal:** No está previsto para despliegue permanente en producción
- **Limpieza:** Elimina marcadores de posición obsoletos para mantener el repositorio ligero
- **Documentación:** Actualiza este README cuando añadas series de marcadores de posición principales

## 📞 ¿Preguntas?

Consulta el [README.md](../README.md) principal para directrices del repositorio o contacta al equipo de Myzon.
