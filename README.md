# Salones Venecia

Sitio web de **Salones Venecia**, salón de bodas, eventos y cafetería en Andújar (Jaén),
con más de 35 años de experiencia en hostelería familiar.

## Stack

- [Astro](https://astro.build) — sitio 100% estático
- [Tailwind CSS v4](https://tailwindcss.com)
- TypeScript
- Sin backend ni base de datos — contacto por teléfono, Instagram y visita presencial

## Desarrollo

```sh
npm install
npm run dev       # http://localhost:4321
npm run build     # genera dist/
npm run preview   # sirve dist/ localmente
```

## Estructura

```
src/
  assets/images/   # fotografías fuente (optimizadas por Astro al build)
  components/
  layouts/
  pages/
  styles/          # design tokens (paleta y tipografía) en global.css
public/            # estáticos servidos tal cual (favicon, robots.txt, etc.)
assets-originales/ # fotos/vídeos originales sin procesar (no se despliegan)
```

## Despliegue

El sitio se despliega automáticamente a GitHub Pages mediante GitHub Actions
en cada push a `main`.
