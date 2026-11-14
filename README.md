# 2e

One static landing page for 2e Digital Works. Vite is used only to produce a
static build; there is no server runtime, CMS, or admin interface.

```sh
pnpm install
pnpm dev
pnpm build
pnpm deploy
```

`pnpm build` writes deployable files to `dist/`. `pnpm deploy` publishes those
assets through Cloudflare Wrangler after authentication.
