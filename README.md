# Demo App for Next.js with Storybook

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/strozw/demo-storybook-nextjs)

## Outline

This demo uses Next.js 15 and React 19 RC to set up a Storybook in `@storybook/nextjs`, with `@storybook/experimental-addon-test` and `vite-plugin-storybook- nextjs` to allow vitest to test components using `*.stories.tsx` and the nextjs API.

### Why not use `@storybook/experimental-nextjs-vite`?

Currently, @storybook/experimental-nextjs-vite` does not support React 19 for rendering storybooks in the browser.
Therefore, I use`@storybook/nextjs`and mock the Next.js API when running vitest on`vite-plugin-storybook-nextjs`.

## Setup

```
pnpm install
```

## NPM Scripts

### Develop

```
pnpm dev
```

### Build APP

```
pnpm build
```

### Develop by Strobyook

```
pnpm storybook
```

### Build Strobyook

```
pnpm build-storybook
```

### Lint

```
pnpm test
```

### Test

```
pnpm test
```
