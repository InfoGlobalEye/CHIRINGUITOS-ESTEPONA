# Playas Estepona — Mapa + Filtros + Precios en (casi) tiempo real

## Despliegue en Vercel (rápido)
1. Crea un proyecto en Vercel y selecciona este repo.
2. Variables de entorno (si más adelante integras APIs externas): crea un `.env` con claves de Google, etc.
3. `npm install` y `npm run build` lo hace Vercel automáticamente.
4. Abre la URL pública y comparte.

## Desarrollo local
```bash
npm install
npm run dev
# http://localhost:3000
```

## Precios en tiempo real
- Endpoint: `/api/precios` (mock). Integraremos después:
  - Google Places (reseñas/precios), cartas online scrapeables,
  - y una Google Sheet publicada (fallback editable).
