# Iconos

Esta carpeta contiene **iconos y conjuntos de iconos** para usar en plugins, mods, sitios web e interfaces de usuario.

## 📋 Propósito

La carpeta `icons/` está designada para:
- Iconos de UI (botones, navegación, acciones, etc.)
- Activos de icono de plugin/mod
- Iconos de aplicación y características
- Familias de iconos y colecciones
- Variaciones de iconos (tamaños, estilos, estados)

## 📝 Convenciones de Nombres

Usa **letras minúsculas y guiones** para todos los nombres de archivo:

```
plugin-icon.svg
settings-gear.png
user-profile-24px.svg
close-button-dark.png
achievement-badge.svg
```

**Formato:** `[nombre-icono]-[variante].[extensión]`

- `nombre-icono`: descriptivo, minúsculas, guiones entre palabras
- `variante`: opcional, describe tamaño o estilo (ej: 16px, 24px, 32px, oscuro, claro)
- `extensión`: formato de archivo

## ✅ Formatos Soportados

| Formato | Caso de Uso | Prioridad |
|---------|-----------|-----------|
| **SVG** | Iconos escalables, uso en web/UI, preferido | ⭐⭐⭐ Alto |
| **PNG** | Tamaños fijos, uso en web/app, alternativa | ⭐⭐⭐ Alto |
| **GIF** | Iconos animados, efectos especiales | ⭐⭐ Medio |
| **JPG/JPEG** | Iconos raster (raro) | ⭐ Bajo |

## 📤 Reglas de Carga

1. **Prefiere SVG para iconos principales** (escala a cualquier tamaño sin pérdida de calidad)
2. **Proporciona versiones PNG** para tamaños comunes (16px, 24px, 32px, 64px)
3. **Usa fondos transparentes** (PNG con canal alfa)
4. **Ancho de trazo consistente** y padding en todos los conjuntos de iconos
5. **Organiza por categoría** si envías colecciones grandes:
   - `icons/ui-controls/` – botones, interruptores, entradas
   - `icons/navigation/` – menús, flechas, pestañas
   - `icons/actions/` – reproducir, pausar, descargar, etc.
   - `icons/social/` – iconos de redes sociales
6. **Incluye especificaciones de tamaño** en el nombre o documentación
7. **Mantén estilo consistente:**
   - Peso de línea/ancho de trazo
   - Radio de esquina (si aplica)
   - Padding y alineación
   - Alineación de paleta de colores

## 📦 Ejemplos

```
icons/
├── plugin-icon.svg                     # Icono de plugin principal
├── plugin-icon-16px.png
├── plugin-icon-24px.png
├── plugin-icon-32px.png
├── plugin-icon-64px.png
├── settings-icon.svg
├── settings-icon-dark.png              # Variante oscura
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

## 🎨 Directrices de Diseño

- **Tamaños estándar:** 16x16, 24x24, 32x32, 48x48, 64x64, 128x128px
- **Peso de línea:** Consistente en todos los iconos de un conjunto (típicamente 1.5-2px)
- **Padding:** Mantén padding interno consistente
- **Basado en cuadrícula:** Diseña en una cuadrícula de píxeles para una apariencia nítida
- **Alineación:** Centra el contenido dentro del lienzo
- **Color:** Usa un solo color o máximo 2-3 colores; asegura contraste
- **Accesibilidad:** Alto contraste para visibilidad, evita diferenciación solo por color

## 🏷️ Categorías Comunes de Iconos

| Categoría | Ejemplos |
|-----------|----------|
| **Navegación** | Inicio, atrás, adelante, menú, cerrar, configuración |
| **Acciones** | Añadir, eliminar, editar, descargar, cargar, compartir, buscar |
| **Estado** | Éxito, error, advertencia, información, cargando, notificación |
| **Medios** | Reproducir, pausar, parar, siguiente, anterior, silencio, volumen |
| **Controles UI** | Botón, casilla, radio, interruptor, deslizador, desplegable |
| **Social** | Facebook, Twitter, Discord, GitHub, YouTube |

## 📞 ¿Preguntas?

Consulta el [README.md](../README.md) principal para directrices del repositorio o contacta al equipo de Myzon.
