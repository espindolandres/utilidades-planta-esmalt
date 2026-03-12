# Centro de Cálculos de Planta

App estática lista para GitHub Pages, pensada para uso en planta desde celulares y tablets.

## Qué incluye

- Dashboard principal con acceso a 3 módulos.
- Módulo de **Silos, traslados y mezclas**.
- Módulo de **Colorantes para esmalte**.
- Módulo de **Tanques**.
- **Modo planta** global para interfaces táctiles.
- **PWA** básica para instalar en el dispositivo.
- Históricos guardados localmente en el navegador del equipo.

## Estructura del repo

```text
/
├── index.html
├── manifest.webmanifest
├── service-worker.js
├── assets/
│   ├── styles.css
│   └── app.js
└── icons/
    ├── icon.svg
    ├── icon-192.png
    └── icon-512.png
```

## Publicación en GitHub Pages

1. Crea un repositorio nuevo en tu GitHub.
2. Sube todos estos archivos manteniendo la misma estructura.
3. Ve a **Settings > Pages**.
4. En **Build and deployment**, selecciona:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Guarda los cambios.
6. GitHub te dará una URL parecida a:
   `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`

## Recomendación de nombre del repo

- `centro-calculos-planta`
- `planta-suite`
- `utilidades-planta`

## Notas

- No necesita Node, React ni compilación.
- Puedes editar fórmulas, tablas o textos directamente en `assets/app.js`.
- Los históricos son locales a cada navegador/dispositivo.
