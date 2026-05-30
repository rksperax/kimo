# KIMO — Hawaii Surf & Travel UI

[![Next.js](https://img.shields.io/badge/Next.js-13-black?logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Chakra UI](https://img.shields.io/badge/Chakra_UI-2-319795?logo=chakra-ui)](https://chakra-ui.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A **Next.js + TypeScript** frontend for a Hawaii surf & travel platform. Built with Chakra UI, Framer Motion, and Swiper — featuring category browsing, highlight cards, and responsive layouts.

Built by [Rajan Kumar](https://github.com/rksperax)

## Features

- Server-side rendered landing page with dynamic categories & highlights
- Responsive sidebar navigation and header
- Swiper-based text carousel and highlight cards
- Chakra UI theming with custom color tokens
- SEO metadata via dedicated SEO component

## Tech Stack

| Layer | Tools |
|-------|-------|
| Framework | Next.js 13, React 18 |
| Language | TypeScript |
| UI | Chakra UI, Framer Motion |
| Carousel | Swiper 9 |

## Getting Started

```bash
# Install dependencies
yarn install

# Start dev server
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
src/
├── components/     # UI components (Header, Sidebar, Highlights, Categories)
├── hooks/          # Custom hooks (useMediaQuery, useScrollDirection)
├── pages/          # Next.js pages & API routes
├── SEO/            # SEO meta component
├── styles/         # Global CSS
└── types/          # TypeScript interfaces
```

## Scripts

| Command | Description |
|---------|-------------|
| `yarn dev` | Start development server |
| `yarn build` | Production build |
| `yarn start` | Start production server |
| `yarn lint` | Run ESLint |

## API

The app fetches data from the KIMO backend:

- `GET /v1/categories` — surf spot categories
- `GET /v1/highlights` — featured highlights

## License

MIT © [Rajan Kumar](https://github.com/rksperax)
