# Cresto Digital — Vercel Mirror

A responsive static website mirrored from `crestodigital.github.io` and configured for Vercel.

## Deploy to Vercel

1. Import `crestodigital/crestodigital-vercel` in Vercel.
2. Set the project name to `crestodigital`.
3. Keep the framework preset as `Other` and leave the build command empty.
4. Deploy from the repository root.

The expected production URL is `https://crestodigital.vercel.app/`, subject to project-name availability.

The canonical metadata intentionally continues to reference the primary GitHub Pages site so the mirror does not create duplicate competing URLs in search results.

## Update contact email

Open `assets/js/script.js` and replace:

```js
contactEmail: "hello@crestodigital.com"
```

Also update the visible email fallback in `index.html` if needed.

## Brand colors

- Navy: `#0B2545`
- Cyan: `#20C5DB`
- Sky: `#00C6E2`
- Orange: `#FF6A3D`
- Light background: `#F5F7FA`
