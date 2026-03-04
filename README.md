# Coberturas Albañilería

PWA de consulta de coberturas de albañilería para reparadores colaboradores.

## Instalación

| Plataforma | Pasos |
|---|---|
| **Android (Chrome)** | Abre la URL → menú ⋮ → "Añadir a pantalla de inicio" |
| **iOS (Safari)** | Abre la URL → botón compartir □↑ → "Añadir a pantalla de inicio" |
| **PC (Chrome / Edge)** | Abre la URL → icono ⊕ en la barra de direcciones → "Instalar" |

## Despliegue en GitHub Pages

1. Sube todos los archivos a un repositorio de GitHub.
2. Ve a **Settings → Pages**.
3. En *Source*, selecciona la rama `main` y carpeta `/ (root)`.
4. Guarda. La app estará disponible en `https://<usuario>.github.io/<repositorio>/`.

## Estructura de archivos

```
├── index.html           ← App principal
├── manifest.json        ← Configuración PWA
├── sw.js                ← Service Worker (offline)
├── favicon.ico          ← Favicon navegador
├── og-image-wide.png    ← Preview redes sociales (1200×630)
├── .nojekyll            ← Necesario para GitHub Pages
└── icons/
    ├── apple-touch-icon.png  (180×180)
    ├── icon-16.png
    ├── icon-32.png
    ├── icon-48.png
    ├── icon-72.png
    ├── icon-96.png
    ├── icon-120.png
    ├── icon-128.png
    ├── icon-144.png
    ├── icon-152.png
    ├── icon-167.png
    ├── icon-180.png
    ├── icon-192.png
    ├── icon-256.png
    ├── icon-384.png
    └── icon-512.png
```

## Notas

- La app funciona **sin conexión** tras la primera carga (Service Worker).
- Herramienta de uso interno. No recoge datos ni interactúa con sistemas corporativos.
