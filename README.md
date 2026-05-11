# QR Gen — PWA Generador de Códigos QR

App web progresiva (PWA) para generar códigos QR **100% offline**, sin costos.

## Archivos

```
qr-pwa/
├── index.html      ← App principal
├── manifest.json   ← Configuración PWA
├── sw.js           ← Service Worker (offline)
├── icon-192.png    ← Ícono app
└── icon-512.png    ← Ícono app (grande)
```

## Publicar en GitHub Pages (gratis)

### Paso 1 — Crear repositorio
1. Entrá a [github.com](https://github.com) → **New repository**
2. Nombre: `qr-gen` (o el que quieras)
3. Marcalo como **Public**
4. Hacé clic en **Create repository**

### Paso 2 — Subir los archivos
Opción A — Desde el navegador (más fácil):
1. En tu repo, hacé clic en **uploading an existing file**
2. Arrastrá los 5 archivos: `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`
3. Clic en **Commit changes**

Opción B — Con Git:
```bash
git clone https://github.com/TU_USUARIO/qr-gen.git
cp /ruta/archivos/* qr-gen/
cd qr-gen
git add .
git commit -m "Inicial"
git push
```

### Paso 3 — Activar GitHub Pages
1. En tu repo → **Settings** → **Pages** (menú lateral)
2. En "Branch" seleccioná **main** y carpeta **/ (root)**
3. Clic en **Save**
4. En 1-2 minutos tu app estará en:
   `https://TU_USUARIO.github.io/qr-gen/`

## Instalar en Android

1. Abrí la URL en **Chrome para Android**
2. Tocá el menú ⋮ → **"Añadir a pantalla de inicio"**
3. ¡Listo! Funciona como una app nativa

## Características

- ✅ Genera QR de cualquier texto o URL
- ✅ Funciona 100% offline tras primera carga
- ✅ Descarga el QR como PNG
- ✅ Colores personalizables
- ✅ Instalable en Android e iOS
- ✅ Sin backend, sin base de datos, sin costos
