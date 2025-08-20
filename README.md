# EsoPlayer Lite (React + Vite + Tailwind)
Un reproductor web para listas de canales `.m3u8` al estilo EsoPlayer.

## 🚀 Stack
- React + Vite
- TailwindCSS
- hls.js

## 📦 Instalación local
```bash
npm install
npm run dev
```
Abre http://localhost:5173/

## 🧪 Añadir canales
Edita `src/canales.json` y agrega objetos con `nombre`, `url`, `logo` y `categoria` si quieres.

## 🏗️ Build de producción
```bash
npm run build
npm run preview
```

## ☁️ Deploy en Netlify
1. Crea un repo en GitHub y sube el proyecto.
2. En Netlify: **Add new site > Import from Git**.
3. Selecciona el repo.
4. Build command: `npm run build`
5. Publish directory: `dist`
6. Deploy.

> Opcional: Incluimos `netlify.toml` por si prefieres configuración por archivo.

## ⚠️ Nota legal
Reproduce únicamente contenidos y streams de los que tengas derecho de uso. Este proyecto es educativo.
