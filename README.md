# Manivannan S. — Personal Portfolio

A responsive personal portfolio for Manivannan S., showcasing work across AI, automation, software development, and product building.

## Overview

The site is built with React, TypeScript, and Vite. It includes:

- An editorial-style hero section and personal introduction
- About and capabilities sections
- Skills and technology stack
- Founder ventures: Qbito Solutions and Ziko Innovation Hub
- Selected project cards
- Experience timeline
- Contact section and social links
- Responsive navigation for smaller screens

## Tech stack

- **React 19** — UI library
- **TypeScript** — type-safe JavaScript
- **Vite** — development server and production bundler
- **CSS** — custom responsive styling
- **Tailwind CSS 4** — included in the project toolchain

## Getting started

### Requirements

- Node.js 20.19+ or 22.12+ (recommended for the Vite 8 toolchain)
- Node package manager via Corepack (the repository includes `pnpm-lock.yaml`)

### Install dependencies

```bash
corepack pnpm install
```

### Start the development server

```bash
corepack pnpm dev
```

Vite will print a local URL, usually `http://localhost:5173`.

### Create a production build

```bash
corepack pnpm build
```

### Preview the production build

```bash
corepack pnpm preview
```

## Project structure

```text
.
├── public/                  # Static files served as-is (add assets here if needed)
├── src/
│   ├── components/          # Reusable UI components
│   │   └── Spark.tsx
│   ├── data/                # Portfolio content and project data
│   │   └── portfolio.ts
│   ├── imports/             # Imported images and original design reference
│   ├── pages/               # Page-level compositions
│   │   └── Home.tsx
│   ├── styles/              # Global styles
│   │   └── global.css
│   ├── App.tsx              # Application root
│   └── main.tsx             # React entry point
├── index.html
├── package.json
├── pnpm-lock.yaml
├── tsconfig.json
└── vite.config.ts
```

## Updating portfolio content

- **Projects and skills:** edit `src/data/portfolio.ts`.
- **Page sections and copy:** edit `src/pages/Home.tsx`.
- **Reusable visual elements:** add components under `src/components/`.
- **Colors, layout, typography, and responsive rules:** edit `src/styles/global.css`.
- **Portrait and other imported images:** place files in `src/imports/` and import them where required.

## Before publishing

Review and replace any placeholder or personal contact details in `src/pages/Home.tsx`, including the contact email and LinkedIn destination. Confirm that project descriptions, venture details, and experience dates are current. Add a real LinkedIn profile URL before launch.

## Deployment

The project can be deployed to any static hosting platform that supports Vite builds, including Vercel, Netlify, or GitHub Pages with the appropriate base-path configuration.

For Vercel, import the repository and use:

- **Build command:** `corepack pnpm build`
- **Output directory:** `dist`
- **Install command:** `corepack pnpm install`

## License

No license has been specified. All rights remain with the project owner unless a license is added to this repository.
