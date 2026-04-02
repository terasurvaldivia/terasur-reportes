# Tera Sur – App de Reportes 📱⚡

Aplicación PWA (Progressive Web App) para reportes de mantención eléctrica y novedades.

---

## 📁 Archivos incluidos

```
terasur-app/
├── index.html       ← La aplicación completa
├── manifest.json    ← Configuración PWA (instalación)
├── sw.js            ← Service Worker (modo offline)
├── logo.png         ← Logo de Tera Sur (DEBES AGREGAR)
└── README.md        ← Este archivo
```

---

## ⚠️ PASO OBLIGATORIO: Agregar el logo

Copia tu archivo de logo como **`logo.png`** dentro de la carpeta `terasur-app/`.
La app detecta automáticamente si no encuentra el logo y usa un texto de reemplazo.

---

## 🚀 Cómo publicar la app (para que tus trabajadores la instalen)

### Opción A – Google Drive + enlace directo (GRATIS, más fácil)

1. Sube toda la carpeta `terasur-app/` a **Google Drive**
2. Comparte el archivo `index.html` con enlace público
3. Tus trabajadores abren el enlace desde su celular/tablet

### Opción B – Hosting gratuito con Netlify (RECOMENDADO para PWA completa)

1. Ve a [netlify.com](https://netlify.com) y crea cuenta gratuita
2. Arrastra la carpeta `terasur-app/` al panel de Netlify
3. Netlify te dará una URL tipo: `https://terasur-reportes.netlify.app`
4. Comparte esa URL con tus trabajadores

---

## 📲 Cómo instalar en Android

1. Abre Chrome en el celular/tablet
2. Ve a la URL de la app
3. Aparece el banner "Agregar a pantalla de inicio" → Toca **Instalar**
4. Si no aparece el banner: menú (⋮) → "Añadir a pantalla de inicio"

## 🍎 Cómo instalar en iPhone / iPad

1. Abre Safari (obligatorio, no Chrome)
2. Ve a la URL de la app
3. Toca el botón **Compartir** (□↑)
4. Toca **"Añadir a pantalla de inicio"**
5. Toca **Agregar**

---

## 📋 Funcionalidades

- ✅ **Configuración inicial** con nombre, cargo y PIN de seguridad
- ✅ **Login con PIN** de 4 dígitos cada vez que se abre
- ✅ **Dashboard** con acceso rápido a reportes
- ✅ **Formulario de Mantención Eléctrica** (basado en tu plantilla Word)
- ✅ **Formulario de Novedad**
- ✅ **Firma digital** del técnico y del cliente
- ✅ **Generación de PDF** con diseño profesional Tera Sur
- ✅ **Historial** de reportes generados
- ✅ **Funciona offline** (sin internet)
- ✅ **Colores de marca** Tera Sur (verde-azul degradado)

---

## 📤 Enviar PDF a Google Drive

Actualmente el PDF se descarga al dispositivo. Para enviarlo a Drive:

### Desde Android:
- Abre la app de Google Drive
- Toca el botón "+" → "Subir"
- Selecciona el PDF de Descargas

### Desde iPhone:
- Abre la app de Google Drive
- Toca "+" → "Subir archivos"
- Busca el PDF en "Descargas" o "Archivos"

### Integración automática con Drive (opcional – requiere desarrollo adicional):
Si quieres que el PDF se suba **automáticamente** a una carpeta específica de Drive,
es necesario configurar la API de Google Drive. Contáctanos para este paso.

---

## 🎨 Colores de la app

| Color | Hex | Uso |
|-------|-----|-----|
| Verde lima | `#a8d832` | Botones, acentos |
| Teal/Turquesa | `#00b4d8` | Gradientes, focus |
| Azul marino | `#1a2744` | Fondo, header |

Basados directamente en el logo de Tera Sur.

---

## 📞 Soporte

Si necesitas ayuda con la instalación o configurar la integración automática con Google Drive, puedes usar Claude en claude.ai para resolver dudas adicionales.
