# Minimal Portfolio Template

A modern, minimalist personal portfolio template built with Astro and Tailwind CSS (v4).

This single-page site is component-driven and fully configurable from a single TypeScript file.

Key points:

- Tech: Astro, Tailwind CSS v4, TypeScript, Tabler Icons
- Content: Centralized in `src/config.ts` for easy customization
- Structure: Reusable components live in `src/components/` and the page is rendered from `src/pages/index.astro`
- Styling: Global styles in `src/styles/global.css` and an accent color system driven from the config
- Behavior: Sections auto-hide when their data is removed from the config

Development

Install dependencies and run locally:

```
npm install
npm run dev
```

Build and preview production:

```
npm run build
npm run preview
```

Customize

- Edit the site content and settings in `src/config.ts`.
- Modify or extend sections in `src/components/`.
- The main single-page layout is `src/pages/index.astro`.

License

See LICENSE.md for licensing details.

