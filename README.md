This is a reproducible example for the following:
https://github.com/vercel/next.js/issues/20761

- Next version: 12.0.7
- Node version: 16.10.0

## How to run

- `yarn` (install dependencies)
- `yarn dev`
- Open http://localhost:3000, see the server console
  - ctx.locale is correct: "en-id"
- Open http://localhost:3000/a (handled by app.render)
  - ctx.locale is undefined 
