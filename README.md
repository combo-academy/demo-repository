# Northstar Studio

A responsive static landing page for a fictional creative studio, styled with Tailwind CSS v4.

## Requirements

- Node.js 20.19+ or 22.12+
- npm

## Develop

```sh
npm install
npm run watch
```

Open `index.html` in a browser. The watch command rebuilds `styles.css` when the HTML or Tailwind input changes.

## Build

```sh
npm run build
```

The site is static: publish `index.html` and the generated `styles.css` together. Google Fonts and the hero image currently load from external URLs. Replace the fictional brand, sample `hello@northstar.example` email address, and image before publishing for a real business.
