# husamuddin.github.io

Personal resume and portfolio site. Deployed to [husamuddin.github.io](https://husamuddin.github.io) via GitHub Pages.

## Stack

- [Astro 6](https://astro.build) — static output
- CSS custom properties design system — terminal/hacker aesthetic, no utility framework
- Tailwind v4 installed, not yet active
- Node.js 22+

## Project structure

```
src/
├── components/
│   ├── Hero.astro
│   ├── Nav.astro
│   ├── Experience.astro
│   ├── Skills.astro
│   ├── Capabilities.astro
│   ├── Projects.astro
│   ├── Education.astro
│   ├── Manifesto.astro
│   ├── Contact.astro
│   └── Footer.astro
├── layouts/
│   └── Layout.astro
├── pages/
│   └── index.astro
└── styles/
    └── global.css
public/
```

## Dev

```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # output → dist/
npm run preview  # preview build locally
```

## Deploy

Push to `main`. GitHub Actions builds and deploys to GitHub Pages automatically via `.github/workflows/deploy.yml`.
