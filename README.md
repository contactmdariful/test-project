# test-project

A new Node.js project intended to become a **Next.js** app with **TypeScript** (App Router).

The app has not been scaffolded yet. Current setup is an npm package (`test-project` v1.0.0) with [dotenv](https://github.com/motdotla/dotenv) for environment variables.

## Tech stack (planned)

- **Runtime:** Node.js
- **Language:** TypeScript (strict)
- **Framework:** Next.js (App Router)
- **Package manager:** npm

## Getting started

Requirements: [Node.js](https://nodejs.org/) 12 or later (dotenv’s minimum; use a current LTS version for Next.js later).

```bash
npm install
```

Environment variables can be loaded with dotenv. Add a `.env` file in the project root (do not commit secrets).

## Scripts

| Script        | Description                          |
| ------------- | ------------------------------------ |
| `npm test`    | Placeholder; no tests yet            |

## Project conventions

When implementation starts:

- Use TypeScript for all app code (`.ts` / `.tsx`). Avoid new `.js` / `.jsx` files.
- Prefer the App Router (`app/`), Server Components by default, and Client Components only when needed (`"use client"`).
- Keep API routes in `app/api/`.

## License

ISC
