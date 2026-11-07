# TS Boilerplate

A minimal starter for Node.js projects written in TypeScript. It comes with the essential dev dependencies and a basic `tsconfig.json`, so you can start coding right away.

## Stack

- **TypeScript**: static typing
- **tsx**: runs `.ts` files directly, with watch mode
- **tsup**: bundles the code for production
- **@types/node**: type definitions for Node.js

## Getting started

```bash
npm install
```

Create a `.env` file in the project root. The dev scripts load it automatically.

## Scripts

| Command               | Description                                |
| --------------------- | ------------------------------------------ |
| `npm run start:dev`   | Runs `src/server.ts` once                  |
| `npm run start:watch` | Runs `src/server.ts` and restarts on changes |
| `npm run dist`        | Builds the project into `dist/`            |
| `npm run start:dist`  | Builds and runs the production output      |

## Structure

```
src/
  server.ts      # entry point
tsconfig.json    # TypeScript config (strict mode)
.env             # environment variables
```
