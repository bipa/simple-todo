# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Commands

**Development:**
- `npm run dev` - Start development server (http://localhost:3000)
- `npm run build` - Build for production with Turbopack
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Architecture

This is a Next.js 15.5.0 application using:
- **App Router** (`app/` directory)
- **TypeScript** with strict mode
- **Tailwind CSS v4** with PostCSS configuration
- **React 19.1.0**

### Key Files
- `app/layout.tsx` - Root layout with Geist font configuration
- `app/page.tsx` - Main page component
- `app/globals.css` - Global styles with Tailwind CSS and CSS custom properties for theming

### Configuration
- TypeScript paths are configured with `@/*` alias pointing to the root directory
- ESLint is configured via `eslint.config.mjs` with Next.js recommended rules
- Tailwind CSS v4 is configured through PostCSS (`postcss.config.mjs`)