# react-router-dom template

A simple starter template for React apps using **Vite**, **react-router-dom** and **Tailwind CSS v4**.

## What's included

- React with Vite
- react-router-dom with a shared `RootLayout` and an `<Outlet />`
- Tailwind CSS v4 via the `@tailwindcss/vite` plugin
- Empty layout and page files, ready to fill in
- ESLint

## Folder structure

```
src/
  assets/      images and other static files
  layouts/     RootLayout, Header, Footer (empty)
  pages/       Home, About, Error (empty)
  App.jsx      route definitions
  main.jsx     entry point (BrowserRouter)
  index.css    Tailwind import
```

## How to use this template

### Option 1: Use this template on GitHub (recommended)

Click **Use this template** at the top of the repo page and create a new repository. You get the files without this repo's git history.

### Option 2: degit

```bash
npx degit SA-Faizeen/react-router-dom-template my-project
```

### Then set it up

```bash
cd my-project
npm install
npm run dev
```

The dev server runs at `http://localhost:5173`.

## Before you start building

- Change the `name` field in `package.json`.
- Update `base` in `vite.config.js` if you deploy to a subpath such as GitHub Pages.
- Fill in the layouts in `src/layouts` and the pages in `src/pages`.
- Add or edit routes in `src/App.jsx`.