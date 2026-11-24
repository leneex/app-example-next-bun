# Next.js on Bun

Example [Next.js](https://nextjs.org/) app running on [Bun](https://bun.sh/). Next.js is a React framework for building full-stack web applications. Bun is a fast all-in-one JavaScript runtime and package manager compatible with Node.js.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Static site — Railpack build |
| Single-page application (SPA) | off |
| Project directory | `/` |
| Output directory | `/out` |
| Install command | leave empty |
| Build command | leave empty |
| Health check path | `/` |

## <a name="dev"></a>Run locally

```bash
# install dependencies
bun install

# run in development mode
bun run dev

# build for production
bun run build
```
