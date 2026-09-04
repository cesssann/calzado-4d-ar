# AERO-MORPH 4D Footwear Website & AR Experience

Este repositorio contiene el código completo para un sitio web de diseño prospectivo de calzado impreso en 4D, con visualización WebGL y Realidad Aumentada (AR) para iOS y Android.

## 📁 Estructura del Proyecto

```
/
├── index.html          # Código fuente (HTML5, CSS3, WebGL / model-viewer)
├── assets/
│   ├── shoe.glb        # Modelo 3D para WebGL y Android (AR Scene Viewer)
│   └── shoe.usdz       # Modelo 3D para iOS (AR Quick Look)
└── README.md           # Guía de publicación
```

## 🚀 Cómo publicar en GitHub Pages

1. **Crear el repositorio en GitHub:**
   - Ve a [GitHub](https://github.com) y crea un nuevo repositorio llamado `calzado-4d-ar` (o el nombre que prefieras).
   - Déjalo como **Público**.

2. **Subir los archivos:**
   - Sube los archivos `index.html`, la carpeta `assets/` (con tus archivos `.glb` y `.usdz` reales) y `README.md`.

3. **Activar GitHub Pages:**
   - Entra a tu repositorio en GitHub.
   - Ve a **Settings** (Configuración) -> **Pages**.
   - En **Source** (Fuente), selecciona la rama `main` (o `master`) y la carpeta `/ (root)`.
   - Haz clic en **Save**.
   - En 1 o 2 minutos, GitHub te dará un enlace público con tu sitio web (ej. `https://tu-usuario.github.io/calzado-4d-ar/`).

## 📱 Requisitos para Realidad Aumentada (AR)
- **Android:** Requiere navegador Chrome con soporte WebXR o la aplicación instalada Google Play Services for AR.
- **iPhone / iPad:** Requiere iOS 12+ (funciona nativamente con AR Quick Look a través del archivo `.usdz`).
