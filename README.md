# Trigly

An interactive trigonometry workspace for exploring `y = a f(bx − c) + d`, with sine, cosine, and tangent graphs.

## Run locally

Requires Node.js 20.19+ or 22.12+.

```sh
npm ci
npm run dev -- --port 3000
```

Open http://localhost:3000. Build the production site with `npm run build`; the static output is in `dist/`.

## Features

- Live graphs with adjustable parameters, parent curves, key points, and tangent asymptotes
- Radian and degree displays, zoom, grid controls, and SVG download
- Calculated amplitude or vertical scale, period, phase shift, and midline
- Worked examples, three step-by-step guides, and four practice questions
- Responsive layouts for desktop and mobile

All interactions run in the browser. The app uses Vite, Lucide icons, and Google Fonts; it has no backend or external API requirements.
