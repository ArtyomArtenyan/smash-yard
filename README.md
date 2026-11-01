# Smash Yard

A fictional burger restaurant website built with React and Vite.

## Development

Run `npm ci`, then `npm run dev`. Use `npm run build` for production and `npm run preview` to preview the build. Opening index.html directly is not supported.

## Features

Five routes: home, searchable menu, burger builder, story, and visit/FAQ. Category and vegetarian filters, ingredient dialogs, live builder pricing and explicit localStorage saving. Responsive navigation and reduced-motion support.

No orders, payments, reservations, accounts or server-side data collection. Restaurant details and prices are illustrative. Food photography is generated imagery. Google Fonts load externally with system-font fallbacks.

## Deployment

Import into Vercel with the Vite preset. Build: `npm run build`. Output: `dist`. The included vercel.json supports direct navigation to client-side routes.

Menu data: src/menu.js. Components: src/main.jsx. Styles: src/style.css. Images: public/assets.
