# Logos

Esta carpeta contiene **logos oficiales de Myzon** y activos de marca para usar en plugins, mods, sitios web y materiales de marketing.

## 📋 Propósito

La carpeta `logos/` está designada para:
- Logos de marca oficial de Myzon
- Activos de marca de empresa/proyecto
- Logos para diferentes casos de uso (horizontal, vertical, cuadrado, etc.)
- Variaciones (modo oscuro, modo claro, monocromático, etc.)

## 📝 Convenciones de Nombres

Usa **letras minúsculas y guiones** para todos los nombres de archivo:

```
myzon-logo-horizontal.svg
myzon-logo-vertical-dark.png
myzon-logo-white-bg.svg
myzon-wordmark.png
myzon-icon-badge.png
```

**Formato:** `[nombre-proyecto]-[descripción-variante].[extensión]`

- `nombre-proyecto`: minúsculas, guiones entre palabras
- `descripción-variante`: opcional, describe la variante (oscuro, claro, horizontal, vertical, etc.)
- `extensión`: formato de archivo

## ✅ Formatos Soportados

| Formato | Caso de Uso | Prioridad |
|---------|-----------|-----------|
| **SVG** | Logos escalables, uso en web, formato preferido | ⭐⭐⭐ Alto |
| **PNG** | Fondos transparentes, uso en web/app | ⭐⭐⭐ Alto |
| **JPG/JPEG** | Fondos, logos a todo color | ⭐⭐ Medio |
| **GIF** | Animaciones, efectos especiales | ⭐ Bajo |

## 📤 Reglas de Carga

1. **Siempre proporciona versiones SVG** cuando sea posible (escalables y versátiles)
2. **Incluye versiones PNG** con fondos transparentes
3. **Usa nombres descriptivos** que indiquen variante/propósito
4. **Organiza por tipo:**
   - Logos principales en la raíz de la carpeta
   - Variantes en subcarpetas si es necesario (ej: `logos/dark-mode/`, `logos/monocrome/`)
5. **Incluye documentación** en un comentario o archivo separado para suites de logo complejas
6. **Mantén calidad:**
   - Mínimo 200x200px para logos pequeños
   - Mínimo 1000x1000px para logos principales/grandes
   - Evita artefactos de compresión

## 📦 Ejemplos

```
logos/
├── myzon-logo-primary.svg              # Logo principal
├── myzon-logo-primary.png              # Versión PNG con transparencia
├── myzon-logo-horizontal.svg           # Variante horizontal
├── myzon-logo-vertical.svg             # Variante vertical
├── myzon-logo-white.png                # Variante blanca para fondos oscuros
├── myzon-logo-dark.png                 # Variante oscura para fondos claros
├── myzon-icon-badge.svg                # Badge de icono simplificado
└── dark-mode/
    ├── myzon-logo-dark-mode.svg
    └── myzon-logo-dark-mode.png
```

## 🎨 Directrices de Diseño

- Mantén consistencia de relación de aspecto
- Usa la paleta de colores oficial de Myzon
- Asegura legibilidad en tamaños pequeños
- Prueba en fondos claros y oscuros
- Preserva espaciado/padding apropiado alrededor del logo

## 📞 ¿Preguntas?

Consulta el [README.md](../README.md) principal para directrices del repositorio o contacta al equipo de Myzon.
