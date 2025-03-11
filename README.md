# Welcome to React Router!

A modern, production-ready template for building full-stack React applications using React Router.

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/remix-run/react-router-templates/tree/main/default)

## Features

- 🚀 Server-side rendering
- ⚡️ Hot Module Replacement (HMR)
- 📦 Asset bundling and optimization
- 🔄 Data loading and mutations
- 🔒 TypeScript by default
- 🎉 TailwindCSS for styling
- 📖 [React Router docs](https://reactrouter.com/)

## Getting Started

### Installation

- node.js v22.14.0 (nvm use 22)
- npm@10.9.2

```bash
npx create-react-router@7.0.1 wemake
```

Install the dependencies:

```bash
npm install
```

- shadcn@2.4.0-canary.12 
  - React Router7 이 React19를 사용해서 호환성 문제가 있음 "--legacy-peer-deps" 옵션을 사용하여 의존성 패키지 설치

```bash
npx shadcn@latest init
```
```bash
Need to install the following packages:
shadcn@2.4.0-canary.12
Ok to proceed? (y) y

✔ Preflight checks.
✔ Verifying framework. Found React Router.
✔ Validating Tailwind CSS config. Found v4.
✔ Validating import alias.
✔ Which color would you like to use as the base color? › Neutral
✔ Writing components.json.
✔ Checking registry.
✔ Updating app/app.css
  Installing dependencies.

It looks like you are using React 19. 
Some packages may fail to install due to peer dependency issues in npm (see https://ui.shadcn.com/react-19).

✔ How would you like to proceed? › Use --legacy-peer-deps
✔ Installing dependencies.
✔ Created 1 file:
  - app/lib/utils.ts

Success! Project initialization completed.
You may now add components.
```

### Development

Start the development server with HMR:

```bash
npm run dev
```

Your application will be available at `http://localhost:5173`.

## Building for Production

Create a production build:

```bash
npm run build
```



## Styling

This template comes with [Tailwind CSS](https://tailwindcss.com/) already configured for a simple default starting experience. You can use whatever CSS framework you prefer.

---

Built with ❤️ using React Router.
