# React + Vite with Tailwind CSS v4

## changes in tailwind v4

- `npx tailwindcss init`  no longer able to used since if remove `tailwind.config.js`
- now you can make  configuration in  css file with the `@theme` directive
- you can write like this in your css (e.g ,index.css) config file 

```css
@theme {
  --font-display: "Satoshi", "sans-serif";
  --breakpoint-3xl: 1920px;
  --color-avocado-100: oklch(0.99 0 0);
  --color-avocado-200: oklch(0.98 0.04 113.22);
  --color-avocado-300: oklch(0.94 0.11 115.03);
  --color-avocado-400: oklch(0.92 0.19 114.08);
  --color-avocado-500: oklch(0.84 0.18 117.33);
  --color-avocado-600: oklch(0.53 0.12 118.34);
  --ease-fluid: cubic-bezier(0.3, 0, 0, 1);
  --ease-snappy: cubic-bezier(0.2, 0, 0, 1);
}`

