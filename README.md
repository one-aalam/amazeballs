[Turborepo](https://turborepo.org/) based mono-repo with multiple meta-frameworks all working in harmony and sharing packages, branched out from Turborepo's official example

## What's inside?

This repository includes the following packages, apps and utilties -

### Available Apps
- `api`: an [Express](https://expressjs.com/) server
- `storefront`: a [Next.js](https://nextjs.org) app
- `admin`: a [Vite](https://vitejs.dev/) single page app
- `blog`: a [Remix](https://remix.run/) blog
- `blog-v2`: a [Astro](https://astro.build/) blog

### Available Packages
- `logger`: isomorphic logger (a small wrapper around console.log)
- `ui`: a dummy React UI library (which contains a single `<CounterButton>` component)
- `scripts`: Jest and eslint configurations
- `tsconfig`: tsconfig.json;s used throughout the monorepo

Everything's 100% done in [Typescript](https://www.typescriptlang.org/).

### Available Utilities

This repo has some additional tools already setup for you -

- [Typescript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Jest](https://jestjs.io) test runner for all things JavaScript
- [Prettier](https://prettier.io) for code formatting
