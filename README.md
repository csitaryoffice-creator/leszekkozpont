# LESZEK KÖZPONT weboldal

Production-ready Vite + React projekt, Vercelre deployolható builddel.

## Fejlesztői indítás

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
```

A build kimenete a `dist` mappa.

## Vercel

Vercel beállítások:

- Framework preset: `Vite`
- Build command: `npm run build`
- Output directory: `dist`

A `vercel.json` tartalmazza az SPA route rewrite szabályt.
