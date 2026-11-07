# The Perfect Brew

An editorial product website for artisanal Ethiopian coffee. Visitors can explore Yirgacheffe, Sidama, and Guji, open origin guides, compare roast levels, and learn about brewing and quality.

Built with React 19, TypeScript, TanStack Start, Vite, and Netlify. Responsive styling uses custom CSS. The coffee photograph is generated and served through Netlify Image CDN; product packaging is composed in CSS. Origin notes describe typical regional characteristics rather than a specific available harvest. This site does not take orders or payments.

## Local development

Use Node 22.13+ or Node 24 and pnpm:

```sh
pnpm install
netlify dev --port 8889
```

Netlify's local server emulates the image CDN. Production builds are handled by Netlify.
