# @rive/doc-vite-plugin

Vite Plugin to wrap MDX and necessary Markdown plugins

## Install

```bash
npm i -D @rive/doc-vite-plugin
```

## Usage

```ts
// vite.config.ts
import { defineConfig } from 'vite';
import doc from '@rive/doc-vite-plugin';

export defult defineConfig({
  plugins: [doc()]
});
```
