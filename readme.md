Run `pnpm exec babel node_modules/vite-plugin-ssr/dist/esm/shared/route.js` (or just run `pnpm run run`) and observe that Babel succesfully transpiles the file, despite the `export` being defined before the referenced `import`, see https://github.com/brillout/vite-plugin-ssr/issues/457.
