# Beach Scroll Cinematic Experience

React 18 + Vite + GSAP ScrollTrigger cinematic sunset-to-night beach scroll experience.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Assets

Place these files in `public/images/`:

- `beach-day.jpg`
- `beach-night.jpg`
- `sun.png`
- `bonfire.png`

## Sun placement

The sun position is controlled in `src/components/BeachScene.module.css`:

```css
.sun {
  top: var(--sun-top, 19%);
  left: var(--sun-left, 62%);
}
```

Adjust those percentages until the PNG sits exactly where the removed sun belongs in your beach-day image.
