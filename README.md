# Home Page Proposal — Jen

Propuesta de home (copia estática para iteración de diseño)

Snapshot estático de la home de [holded.com/es](https://www.holded.com/es) preparado para **iterar sobre las imágenes de producto** y compartir propuestas con el equipo.

> ⚠️ Copia interna de trabajo. No es el sitio de producción. Uso interno del equipo de Holded.

## Qué es

- `index.html` — la home renderizada, con todas las rutas apuntando a assets locales.
- `assets/` — CSS, fuentes e imágenes descargadas del original.
- Se ha eliminado el JavaScript de hidratación para que sea un estático estable (no hay interacciones dinámicas; el objetivo es visual).

## Cómo verlo en local

```bash
cd holded-home-copia
python3 -m http.server 4599
# abre http://localhost:4599
```

## Cómo cambiar las imágenes de producto

Las imágenes están en `assets/images/`. Las principales de producto:

- `assets/images/home/cloud/es/` — capturas de producto (team, inventory, projects, crm…)
- `assets/images/home/video/thumbnail-es.webp` — miniatura del vídeo
- `assets/images/integrations/` — logos de integraciones
- `assets/images/logos/clients/` — logos de clientes

Sustituye el archivo manteniendo el mismo nombre y formato y recarga la página.
