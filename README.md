# React Pure ERC1155 Swap (React.js)

![Modern Neon Sci-Fi Fantasy Book Cover copy](https://github.com/FanbaseLabs/React-Aggregate-ERC20-Swap/assets/145924938/277ca724-0bf4-4815-a4f9-12a26d467a69)

This repository is a minimal React app that renders `fanbase-pure-1155-swap-widget` on the main page.

## What is in the code

- `src/App.tsx`: renders `NftExchangeWidget` from `fanbase-pure-1155-swap-widget`.
- `src/index.tsx`: React entry point that mounts the app.
- `src/App.css`: basic app-level styles.

## Install and run

```bash
npm install
npm start
```

Open `http://localhost:3000`.

## Available scripts

- `npm start`: start local development server.
- `npm run build`: create production build.
- `npm test`: run tests.
- `npm run eject`: eject CRA config (one-way operation).

## Widget docs

Pure swap widget reference:
https://fanbase-io.gitbook.io/docs/reference/swap-widget-sdk/pure-swap-widget

Plan/app access:
https://www.plan.fanbase.io

## Notes

- Current widget configuration is in `src/App.tsx` (`appId` and `chainId`).
- If you change widget package usage in code, keep `package.json` dependencies in sync.
