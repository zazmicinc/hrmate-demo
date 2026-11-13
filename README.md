# HR Mate demo

Clickable demos for HR Mate, on fictional data. Nothing here calls a model or a real HR system.

| App | What | Run |
|---|---|---|
| [apps/prototype](apps/prototype) | The redesigned HR Mate admin panel and Google Chat bot cards, built with shadcn/ui | `pnpm prototype` |

```bash
pnpm install
pnpm prototype      # http://localhost:5173
pnpm typecheck
pnpm build
```

Needs Node 22.12 or newer and pnpm 9. The prototype's own README has the click-through script.

## Hosting

`.github/workflows/pages.yml` builds the apps and publishes them to GitHub Pages on every push to `main`. Turn Pages on once in Settings → Pages (Source: GitHub Actions). A password screen is optional: add a `DEMO_PASSWORD` repository secret and re-run the workflow. It keeps casual visitors out; it is not access control.
