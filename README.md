# Ankit Maurya | Kage Portfolio

A Japanese-inspired developer portfolio featuring an immersive 3D scene, custom visual effects, project presentations, technical skills, and contact information.

## Overview

This project uses a React and TypeScript application powered by Vite to serve a custom HTML portfolio experience in a full-viewport iframe. The portfolio page uses Three.js and its associated assets for the 3D visual experience.

## Technology Stack

### Application
- React: UI framework (`react`, `react-dom`)
- TypeScript: static typing and build-time checks
- Vite: development server and production build
- HTML and CSS: portfolio structure, layout, styling, and animations

### 3D and Visual Experience
- Three.js (`three`): 3D rendering
- Custom HTML, CSS, JavaScript, and visual assets in `public/landing-pages/`

### Development Tools
- npm: package and dependency management
- ESLint: code linting
- TypeScript compiler: type checking

## Dependencies

### Runtime dependencies
- `react`
- `react-dom`
- `three`

### Development dependencies
- `vite` and `@vitejs/plugin-react`
- `typescript`
- `eslint` and the configured ESLint plugins
- React and Node.js type definitions
- Supporting lint configuration packages

Exact version ranges are defined in `package.json`; `package-lock.json` records the resolved dependency tree for reproducible installation.

## Project Structure

```text
portfolio-kage/
|-- public/
|   |-- favicon.svg
|   |-- icons.svg
|   `-- landing-pages/
|       |-- kage-portfolio-preview.html
|       `-- secret-pathways-assets/
|-- src/
|   |-- App.tsx
|   |-- index.css
|   `-- main.tsx
|-- index.html
|-- package.json
|-- package-lock.json
|-- tsconfig.json
|-- tsconfig.app.json
|-- tsconfig.node.json
|-- vite.config.ts
|-- eslint.config.js
|-- .gitignore
`-- README.md
``

## Requirements

- Node.js compatible with the Vite version specified in `package.json`
- npm

## Run Locally

Install the locked dependencies:

```bash
npm ci
```

Start the development server:

```bash
npm run dev
```

Open the local URL printed by Vite.

## Available Commands

| Command | Purpose |
| --- | --- |
| `npm run dev` | Start the development server |
| `npm run build` | Run TypeScript project checks and create the production build |
| `npm run lint` | Run ESLint |
| `npm run preview` | Preview the production build locally |

## Production Build

```bash
npm run build
```

The generated site is written to `dist/`. Deploy the contents of that directory using a static hosting provider configured for the Vite build. Keep the HTML file and its referenced assets at their expected paths so the portfolio loads correctly.

## Maintenance Notes

- Keep `package.json` and `package-lock.json` together.
- Do not commit `node_modules/` or generated `dist/` output.
- Review the portfolio HTML and its referenced assets before removing or renaming files.
- Verify the production build and inspect the deployed site before considering a release complete.

## Author

**Ankit Maurya**

- GitHub: https://github.com/Ankit-code02
- LinkedIn: https://www.linkedin.com/in/ankit0209/
- Portfolio: https://vercel.com/ankit-8772/portfolio-kage/3k5ifG8x8n44nnDrmfhRue6UUo3Y






