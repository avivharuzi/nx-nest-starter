# Nx Nest Starter

Nx workspace with Nest application template with extra features.

## Nx Version

15.6.1

## Nest Version

9.0.0

## ✨ Features

✅ Nx

✅ Jest (unit testing)

✅ ESLint

✅ Prettier (format code style)

✅ Husky (git hooks)

✅ Commitizen

## 🎯 Prerequisites

- Node.js (>= 18 required)
- npm package manager (>= 8 required)

## 🎢 Getting Started

- Replace all `nx-nest-starter` keyword from this project with your new project name, for example: `my-website` and `myWebsite`
- Update this `README.md` file according to your project changes
- If you are using monorepo multi-package repository consider removing `husky` (git hooks) npm package to prevent conflicts between repos, I recommended deleting `.husky` directory, remove npm `prepare` script and run: `npm uninstall husky` and then maybe to add `husky` in the root of the project

## 🕹 Commands

Serve project in development mode.

```bash
npm start
```

Build project for production.

```bash
npm run build
```

Test project.

```bash
npm test
```

Lint project.

```bash
npm run lint
```

Run commitizen.

```bash
npm run cz
```
