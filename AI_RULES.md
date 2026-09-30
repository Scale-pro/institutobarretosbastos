# AI_RULES.md

Project guidance for all AI assistants working on this app.

## Project Context

- Marketing site for **Instituto Barreto Bastos** (endocrinology & clinical nutrition clinic, Cambuí, Campinas/SP, Brazil).
- All user-facing content must be written in **Brazilian Portuguese (pt-BR)**.
- `DESIGN.md` is the design system source of truth (colors, typography, spacing, radii, component specs). Follow it for any visual work.
- The root `index.html` is the original static prototype. New work happens in the React app under `src/` — port existing sections into React components rather than editing `index.html` when building features.

## Tech Stack

- **React + TypeScript** — the entire app is a React SPA written in TypeScript (strict typing, no plain JS).
- **Vite** — dev server and build tool; rely on hot reload for iteration, don't add custom bundler config unless required.
- **Tailwind CSS** — the only styling system. Use utility classes for all layout, spacing, colors, and typography. Design tokens (palette, fonts, radii, spacing) come from `DESIGN.md`.
- **React Router** — client-side routing. All routes stay centralized in `src/App.tsx`.
- **shadcn/ui** — the component library. All components and their dependencies are already installed in `src/components/ui`.
- **Radix UI** — primitives underneath shadcn/ui (dialogs, dropdowns, tabs, etc.). Use them through shadcn/ui, not directly.
- **lucide-react** — the icon library for React components (replaces the Material Symbols used in the static prototype).
- **Fonts** — Playfair Display for headlines, Plus Jakarta Sans for body/labels (per `DESIGN.md`); loaded via Google Fonts.
- **No backend** — currently a static marketing site; forms are front-end only for now.

## Library Rules

| Need | Use | Don't |
|---|---|---|
| UI components (button, card, dialog, tabs, form controls…) | shadcn/ui from `src/components/ui` | Don't write custom components that duplicate shadcn/ui; don't edit files in `src/components/ui` — create new components instead |
| Icons | `lucide-react` | Don't use emoji, other icon packs, or Material Symbols in React code |
| Styling | Tailwind utility classes + tokens from `DESIGN.md` | Don't add external CSS files, CSS-in-JS, or inline `style` objects (except unavoidable dynamic values) |
| Routing | React Router, routes kept in `src/App.tsx` | Don't scatter route definitions across components; don't use `<a href>` for internal navigation |
| Forms | shadcn/ui form components | Don't add new form/state libraries unless explicitly requested |
| Animations | Tailwind transition/animation utilities | Don't add animation libraries (framer-motion, etc.) without a specific need |
| New dependencies | Ask/check first — the preinstalled set covers almost everything | Don't install packages speculatively |

## Code Organization Rules

- All source code lives in `src/`.
- Pages go in `src/pages/`; the main (default) page is `src/pages/Index.tsx`.
- Reusable components go in `src/components/`.
- **Always update `src/pages/Index.tsx` (and routes in `src/App.tsx`) to include new components** — otherwise they never appear in the preview.
- Keep files small and focused; prefer composing sections as separate components (e.g., `Hero`, `Specialties`, `Faq`, `Footer`) matching the sections in `index.html`/`DESIGN.md`.
