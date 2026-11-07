# The Perfect Brew

This is an educational coffee product website using React 19, TanStack Start, TypeScript, and Netlify's Vite adapter.

- `src/routes/index.tsx` renders the homepage.
- `src/components/MarketingPage.tsx` owns the origin collection, keyboard-accessible detail dialogs, region selector, stylized map, roast comparison, and native FAQ disclosures. Regional content is kept in typed local constants; it is editorial content, not persistent application state.
- `src/data/site.ts` defines site title and description, used by the root route's head metadata. Do not add an Open Graph image; the platform supplies it.
- `src/styles.css` contains the forest green and parchment design, responsive layouts, CSS coffee packaging, and reduced-motion rules.
- `public/img/ethiopian-coffee.png` is the generated hero image. Reference it through Netlify Image CDN rather than serving full-resolution output.

Use semantic HTML and accessible buttons. Browser APIs belong in effects or event handlers. Retain dialog focus management, Escape handling, scroll lock, and focus restoration. The geographic illustration is stylized rather than a precise map. Tasting notes are typical origin characteristics and should not imply verified lot specifications. There is no cart, payment processing, contact form, or backend data requirement.

Use pnpm and retain the lockfile. Netlify handles production validation. Do not add persistence unless a new feature needs it; use Netlify platform storage when it does.
