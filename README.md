# LINI JupyterLite

[![lite-badge](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://jupyterlite.github.io/demo)

JupyterLite ejecutándose como un sitio estático en GitHub Pages.

## Pruébalo en

https://oscarys.github.io/lini-jupyterlite/lab/index.html

## Guía de despliegue de JupyterLite en GitHub Pages

https://jupyterlite.readthedocs.io/en/latest/quickstart/deploy.html

## Para actualizar o agregar un notebook

1. Modifica o agrega el notebook en la carpeta `contents/`
2. Actualiza `contentsStorageName` en `jupyter-lite.json` con la fecha de hoy:
   `"lini-jupyterlite-YYYY-MM-DD"`
3. Actualiza ambos archivos (commit)
4. Espera en Actions a que la actualización termine (~2 min)
