# Dyonic IP

Inspired from [sveltekit-on-the-edge](https://github.com/Rich-Harris/sveltekit-on-the-edge) and [react-on-the-edge](https://github.com/vercel-labs/react-on-the-edge). It uses [Nuxt 3](https://v3.nuxtjs.org/) and [Nitro](https://nitro.unjs.io/) to deploy **Vue** based SSR on the edge.

**Online Demo:** https://ip.dyonic.co

## Setup

Enable corepack:

```bash
npx corepack enable
```

Make sure to install the dependencies:

```bash
yarn install
```

## Development

Start the development server on http://localhost:3000

```bash
yarn dev
```

## Production

The easiest way to deploy your app is to link the repo to your Vercel account. Alternatively, you can create a production build locally using `yarn build`.

Checkout the [deployment documentation](https://v3.nuxtjs.org/guide/deploy/presets) for more information.
