# 📈 Stocks App

![Next.js](https://img.shields.io/badge/Next.js-15-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Status](https://img.shields.io/badge/Status-Early%20Setup-orange?style=flat-square)

A stocks app I've started building with **Next.js 15, React 19, TypeScript, Tailwind CSS v4 and shadcn/ui**. 🚧

Right now it's at the **foundation stage**: the project is set up with the App Router, Turbopack, Tailwind v4 and shadcn/ui, with a single test page to make sure everything is wired up correctly. The actual features come next.

---

## 🛠️ Tech stack

| Area | Tools |
| ---- | ----- |
| Framework | Next.js 15 (App Router, Turbopack) |
| Language | TypeScript |
| UI | React 19, Tailwind CSS v4, shadcn/ui, Radix UI, Lucide icons |
| Utilities | `clsx`, `tailwind-merge`, `class-variance-authority` |
| Linting | ESLint |

## 🚀 Getting started

```bash
git clone https://github.com/abdullahaljubayer-101/stocks-app.git
cd stocks-app
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Scripts

| Command | What it does |
| ------- | ------------ |
| `npm run dev` | Start the dev server (Turbopack) |
| `npm run build` | Build for production |
| `npm start` | Run the production build |
| `npm run lint` | Lint the code |

## 📁 Project structure

```text
stocks-app/
├── app/
│   ├── layout.tsx     # Root layout
│   ├── page.tsx       # Home page
│   └── globals.css    # Tailwind + theme
├── lib/utils.ts       # cn() helper for class names
└── components.json    # shadcn/ui config
```

---

Made by **Abdullah Al Jubayer** · [GitHub](https://github.com/abdullahaljubayer-101) · [Portfolio](https://abdullahaljubayer.com)
