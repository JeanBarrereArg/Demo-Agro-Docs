# AgroDocs, demo de lectura automática de comprobantes

Demo interactiva para empresas agropecuarias: carga de facturas y liquidaciones de granos por foto, identificación y clasificación del documento, extracción de importes, fechas, impuestos y vencimientos, y centralización de la documentación.

Es un único archivo `index.html` (HTML, CSS y JavaScript). No necesita instalación ni servidor: se abre con doble clic en cualquier navegador. Todos los datos son simulados.

## Secciones

- **Cargar comprobante**: foto o archivo, más 4 comprobantes de ejemplo con lectura completa.
- **Documentos**: repositorio con búsqueda, filtros por tipo, ficha de detalle y exportación a CSV.
- **Vencimientos**: línea de tiempo de pagos y cobros.
- **Resumen**: cobros contra pagos a 15 días y clasificación de documentos.

## Publicar en Render

1. Subí esta carpeta a un repositorio de GitHub (por ejemplo con GitHub Desktop: *Add existing repository* y luego *Publish repository*).
2. En [dashboard.render.com](https://dashboard.render.com) elegí **New > Static Site** y conectá el repositorio.
3. Configuración:
   - Build Command: dejar vacío
   - Publish Directory: `.`
4. Crear el sitio. Render da un link del tipo `https://agrodocs-demo.onrender.com` para compartir.

Como alternativa, el archivo `render.yaml` permite crearlo desde **New > Blueprint**.

Cada vez que subas cambios al repositorio, Render vuelve a publicar solo.
