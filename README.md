# Lumen — XLM Portfolio Tracker

A responsive cryptocurrency portfolio dashboard built with **React, TypeScript, Vite, Recharts, and Lucide icons**.

## Features

- Portfolio overview cards for total value, XLM balance, performance, and asset count
- Interactive performance chart with 1D, 1W, 1M, 3M, 1Y, and all-time ranges
- Asset allocation visualisation
- Searchable holdings table with prices, daily changes, quantities, and values
- Add holdings and update existing quantities
- Hide/show portfolio balances
- Export portfolio holdings to CSV
- Responsive sidebar and mobile layout
- Accessible controls, reduced-motion support, and toast feedback

## Run locally

Requirements: Node.js 20+ and npm.

```bash
npm install
npm run dev
```

Create a production build:

```bash
npm run build
npm run preview
```

## Deploy

This project can be deployed to Vercel, Netlify, or GitHub Pages. For GitHub Pages, configure the Vite base path if deploying under a repository subpath, then use a GitHub Actions workflow to build and publish the `dist` directory.

## Data note

This version uses illustrative demo prices and sample holdings. It does **not** connect to a wallet, exchange, or live market API, and does not execute transactions. Values are for UI demonstration only and are not financial advice. Replace the sample data and chart series in `src/App.tsx` with a trusted price feed before relying on market values.
