# ZansAI Landing Page

![ZansAI Banner](/public/favicon.svg)

A modern, high-performance landing page for **ZansAI**, built with [Astro](https://astro.build).

## 🚀 Features

- **Modern Design**: Clean, light-themed aesthetic with glassmorphism and animated gradients.
- **Responsive Layout**: Fully responsive design that looks great on all devices.
- **Multi-Page Structure**:
  - **Landing Page**: Hero, Features, Trust Metrics, Pricing, CTA.
  - **Auth**: Sign In (`/signin`) and Get Started (`/get-started`) flows.
  - **Payment Gateway**: Secure checkout page (`/checkout`) with dynamic plan selection.
  - **Resources**: Documentation, Help Center, Community, and Status pages.
  - **Legal**: Privacy Policy, Terms of Service, Security, and Cookie Policy.
- **Performance**: Static site generation (SSG) for blazing fast load times.

## 🛠️ Tech Stack

- **Framework**: [Astro v5](https://astro.build)
- **Styling**: Vanilla CSS (Scoped & Global variables)
- **Icons**: SVG & Unicode
- **Font**: [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts
- **Deployment**: Vercel

## 📦 Project Structure

```text
/
├── public/           # Static assets
├── src/
│   ├── components/   # Reusable Astro components (Navbar, Hero, Pricing, etc.)
│   ├── layouts/      # Page layouts (Layout.astro, LegalLayout.astro)
│   └── pages/        # Route definitions
│       ├── index.astro         # Home page
│       ├── signin.astro        # Sign In page
│       ├── get-started.astro   # Onboarding page
│       ├── checkout.astro      # Payment gateway
│       └── ...                 # Resource & Legal pages
└── astro.config.mjs  # Astro configuration
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |

## 🚀 Deployment

This project is configured for seamless deployment on [Vercel](https://vercel.com).

1.  Push code to GitHub.
2.  Import project in Vercel.
3.  Vercel will automatically detect Astro and configure the build settings.

## 📄 License

© 2025 ZansAI Technologies Inc. All rights reserved.