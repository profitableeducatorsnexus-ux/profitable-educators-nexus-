# Profitable Educators Nexus

Astro website for Profitable Educators Nexus, a program of A+ Educators.

## Local development

```bash
npm install
npm run dev
```

Open `http://localhost:4321` in your browser. The payment confirmation page is available at `/thank-you/`.

## Production build

```bash
npm run build
npm run preview
```

The project uses Astro, Tailwind CSS v4, and GSAP/ScrollTrigger. Netlify publishes the generated `dist/` directory using the configuration in `netlify.toml`.

## Project structure

- `src/pages/` — Astro routes for the homepage and payment confirmation page.
- `src/styles/` — Tailwind v4 theme and global component utilities.
- `public/assets/brand/` — active logo and tier icon assets.
- `public/assets/media/` — video poster and training video.
- `dist/` — generated only during builds and intentionally ignored.
