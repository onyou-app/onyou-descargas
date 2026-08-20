# Descargas de OnYou

Este repositorio solo hospeda los **instaladores oficiales** de
[OnYou](https://on-you.app) en su sección de *Releases*. El código de la app
no vive aquí.

## Descargar

- **Windows**: [OnYou-Instalador.exe (última versión)](https://github.com/dkarolys/onyou-descargas/releases/latest/download/OnYou-Instalador.exe)
- Todas las plataformas: https://on-you.app/descargas

## Para publicar una versión nueva (nota interna)

1. En `onyou-escritorio`: `node empaquetar.mjs` y `npm run construir`.
2. Aquí en GitHub: *Releases → Draft a new release*, tag `vX.Y.Z`,
   arrastrar `dist/OnYou-Instalador.exe` y publicar.

El enlace `releases/latest/download/OnYou-Instalador.exe` siempre entrega la
última versión publicada, así que la página de descargas nunca cambia.
