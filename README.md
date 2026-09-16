# City Drive Times

A personal GIS project mapping the top 10 most populous U.S. cities, with data served live from a Supabase (Postgres) backend.

**Live site:** https://k97x.github.io/city_drivetimes/

## Stack
- **Frontend:** static HTML, CSS, and JavaScript, hosted on GitHub Pages
- **Map:** Leaflet.js with CartoDB dark-matter tiles
- **Backend:** Supabase (Postgres database + auto-generated REST API)
- **Data:** U.S. Census Bureau, Vintage 2024 city population estimates

## Data
City pins are read live from a `cdt_cities` table in Supabase — city, state, population, notes, source, and lat/long centroid per row.

## Roadmap
- User accounts + authentication for editable pins
- Drive-time isochrone tool (via OpenRouteService)
