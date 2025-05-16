# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Build Commands
- `npm install` - Install dependencies
- `npm run dev` - Start local dev server at localhost:4321
- `npm run build` - Build production site to ./dist/
- `npm run preview` - Preview build locally before deploying
- `npm run astro ...` - Run CLI commands like `astro add`, `astro check`

## Code Style Guidelines
- **Imports**: Group imports by type (components, icons, styles)
- **Component Structure**: Front matter (---) contains imports and props at top
- **Styling**: Use Tailwind CSS classes following utility-first approach
- **TypeScript**: Use non-null assertion (!) where appropriate for DOM elements
- **Naming**: Components use PascalCase, variables use camelCase
- **Icons**: Icon components should accept class prop for sizing
- **Accessibility**: Include aria labels, use semantic HTML
- **Responsive Design**: Use size classes (text-sm/lg, etc.) and responsive modifiers
- **Colors**: Use pink-400 as primary accent color
- **Animation**: Use transition classes for smooth interactions