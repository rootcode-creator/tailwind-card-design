# tailwind-card-design — README

Simple responsive newsletter card web app built with Vite + Tailwind CSS v4 and deployed with GitHub Pages.

## Table of Contents

- [🚀 Project intro](#-project-intro)
- [📁 Project structure](#-project-structure)
- [🔧 Features](#-features)
- [🧰 Tech stack](#-tech-stack)
- [⚙️ Install methods](#️-install-methods)
	- [📦 npm / Node](#-npm--node)
- [📜 Available scripts](#-available-scripts)
- [🚀 Deployment notes](#-deployment-notes)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

## 🚀 Project intro

`tailwind-card-design` is a clean, single-page newsletter subscription card UI.
It focuses on layout, typography, and utility-first styling using Tailwind CSS.

## 📁 Project structure

```txt
tailwind-card-design/
├── images/
├── index.html
├── package.json
├── package-lock.json
├── postcss.config.mjs
├── style.css
└── vite.config.js
```

## 🔧 Features

- Responsive newsletter card layout 
- Gradient header banner
- Email input and subscribe button UI
- Tailwind CSS v4 styling with utility classes
- GitHub Pages deployment support via `gh-pages`

## 🧰 Tech stack

- **Build tool:** Vite
- **Styling:** Tailwind CSS v4 + PostCSS
- **Language:** HTML + CSS
- **Deployment:** GitHub Pages

## ⚙️ Install methods

### 📦 npm / Node

Prerequisites:

- Node.js 18+
- npm

```bash
git clone https://github.com/rootcode-creator/tailwind-card-design.git
cd tailwind-card-design
npm install
```

Start local dev server:

```bash
npm run start
```

Build production files:

```bash
npm run build
```

## 📜 Available scripts

```bash
npm run start      # start Vite dev server
npm run build      # create production build in dist/
npm run predeploy  # runs build before deployment
npm run deploy     # deploy dist/ to GitHub Pages
```

## 🚀 Deployment notes

- This project uses `gh-pages` and publishes the `dist/` folder.
- `vite.config.js` uses base path:
	- `/tailwind-card-design`
- If repository name changes, update:
	- `homepage` in `package.json`
	- `base` in `vite.config.js`

## 🤝 Contributing

- Fork the repository and create a feature branch.
- Keep pull requests focused and include clear change descriptions.
- Do not commit secrets or local environment files.

## 📄 License

No license file is currently present in this repository.
If you want this project open-source, add a `LICENSE` file (for example MIT).
