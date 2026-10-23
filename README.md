# @lerna-labs/ekklesia-ui

Shared Svelte components and theme for the Ekklesia platform, used by the voter frontend and the operator console.

## Install

```sh
npm install @lerna-labs/ekklesia-ui
```

The package requires Node 20 or later and Svelte 5.

## Subpath exports

None yet.

## Development

```sh
npm ci
npm run lint
npm run check
npm run build
```

`npm run build` packages `src/lib` into `dist/` and runs `publint` over the result.
