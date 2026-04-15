# Node.js TypeScript Template

A Node.js project template with TypeScript, ESLint, and Prettier configured.

## Prerequisites

- Node.js 20.14.0 or higher
- pnpm 9.x or higher

## Getting Started

```shell script
pnpm install
```


## Running the Project

### Start Development Mode
Runs TypeScript in watch mode and transpiles on file changes.

```shell script
pnpm start:dev
```


### Start Production Mode
Compiles and runs the application in production mode.

```shell script
pnpm start:prod
```


### Build the Project
Compiles TypeScript to JavaScript and applies aliases.

```shell script
pnpm build
```


### Run Linting and Formatting
Checks and fixes code style.

```shell script
pnpm lint
pnpm format
```


## File Structure

```
node-typescript
├── src
├── .dockerignore
├── .prettierrc
├── Dockerfile
├── eslint.config.mjs
├── LICENSE
├── package.json
├── pnpm-lock.yaml
├── pnpm-workspace.yaml
├── tsconfig.build.json
├── tsconfig.json
```


## Useful Commands

| Command           | Description |
|-------------------|-------------|
| `pnpm start:dev`  | Start development server with hot reload |
| `pnpm start:prod` | Start production server |
| `pnpm build`      | Build project (dev) |
| `pnpm build:prod` | Build project (production) |
| `pnpm type:check` | TypeScript type checking |
| `pnpm clean`      | Remove dist directory |
| `pnpm lint`       | Run ESLint |
| `pnpm format`     | Run Prettier |