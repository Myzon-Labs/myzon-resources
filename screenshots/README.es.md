# Capturas de Pantalla

Esta carpeta contiene **capturas de pantalla y documentación visual** para plugins, mods, características e interfaces de usuario.

## 📋 Propósito

La carpeta `screenshots/` está designada para:
- Demostraciones de características de plugin/mod
- Vistas previas de interfaz de usuario
- Capturas de pantalla de tutorial y documentación
- Comparaciones antes/después
- Activos visuales de notas de lanzamiento
- Capturas de pantalla de marketing y promoción

## 📝 Convenciones de Nombres

Usa **letras minúsculas y guiones** para todos los nombres de archivo, incluyendo el nombre del plugin/mod:

```
plugin-name-main-interface.png
plugin-name-settings-page.jpg
feature-demo-01.png
tutorial-step-01-setup.png
comparison-before-after.png
```

**Formato:** `[nombre-proyecto]-[característica/sección]-[descripción].[extensión]`

- `nombre-proyecto`: minúsculas, guiones entre palabras
- `característica/sección`: lo que muestra la captura (ej: main-interface, settings, config)
- `descripción`: opcional, contexto adicional (ej: 01, 02 para secuencias)
- `extensión`: formato de archivo

## ✅ Formatos Soportados

| Formato | Caso de Uso | Prioridad |
|---------|-----------|-----------|
| **PNG** | Capturas de pantalla, calidad sin pérdidas, preferido | ⭐⭐⭐ Alto |
| **JPG/JPEG** | Archivos más grandes, aceptable para fotos | ⭐⭐⭐ Alto |
| **GIF** | Demostraciones animadas, secuencias de pasos | ⭐⭐ Medio |

## 📤 Reglas de Carga

1. **Usa PNG para mejor calidad** (compresión sin pérdidas)
2. **Tamaño máximo de archivo:** 2-5 MB por imagen (optimiza antes de cargar)
3. **Resolución mínima:** 1024x768px para pantalla completa; mantén relación de aspecto
4. **Resolución recomendada:** 1280x720px o 1920x1080px para pantallas estándar
5. **Incluye contexto:**
   - Añade nombres de archivo descriptivos con versión/fecha si es necesario
   - Actualiza este README con breves descripciones
6. **Organiza por plugin/mod:**
   - `screenshots/plugin-name/` o prefija nombres de archivo con nombre del plugin
7. **Mejores prácticas de captura de pantalla:**
   - Elimina información personal y datos sensibles
   - Usa tamaños de ventana consistentes
   - Limpia el escritorio/UI antes de capturar
   - Usa DPI alto para claridad
8. **Para imágenes de comparación:**
   - Mantén capturas antes/después consistentes (misma resolución, recortes similares)
   - Etiqueta claramente o separa por nombre

## 📦 Ejemplos

```
screenshots/
├── myzon-core-main-interface.png       # UI principal
├── myzon-core-settings-panel.png       # Pantalla de configuración
├── myzon-core-dashboard.png            # Vista de panel
├── feature-demo-animation.gif          # Demo animado
├── plugin-name/
│   ├── main-screen.png
│   ├── feature-1-demo.png
│   ├── feature-2-demo.png
│   └── settings-config.png
├── tutorial-step-01-launch.png
├── tutorial-step-02-configure.png
├── tutorial-step-03-complete.png
└── comparison-before-after.png
```

## 📏 Dimensiones Recomendadas

| Caso de Uso | Tamaño Recomendado | Relación de Aspecto |
|-------------|-------------------|-------------------|
| **UI Completa** | 1280x720px | 16:9 |
| **Aplicación de Escritorio** | 1920x1080px | 16:9 |
| **Aplicación Móvil** | 1080x1920px | 9:16 |
| **Detalle de Característica** | 1024x768px | 4:3 |
| **Comparación** | 2560x720px | 16:4.5 |

## 🎨 Directrices de Diseño

- **Encuadre consistente:** Usa mismo tamaño de ventana/pantalla para series
- **Claridad:** Asegura que el texto sea legible (mínimo 12pt visible)
- **Resaltado:** Usa anotaciones o flechas para resaltar características clave
- **Consistencia:** Coincide con tema/marca en todas las capturas de pantalla
- **Limpieza:** Elimina desorden, datos personales o contenido de prueba
- **Marcas de tiempo:** Incluye versión/fecha si es relevante (en nombre o superposición)

## 📋 Formato de Documentación

Cuando añadas múltiples capturas de pantalla relacionadas, actualiza este README:

```markdown
### Nombre del Plugin - Nombre de la Característica
- **plugin-name-feature-screenshot-01.png** – Estado inicial
- **plugin-name-feature-screenshot-02.png** – Después de configuración
- **plugin-name-feature-screenshot-03.png** – Resultado final
```

## 📞 ¿Preguntas?

Consulta el [README.md](../README.md) principal para directrices del repositorio o contacta al equipo de Myzon.
