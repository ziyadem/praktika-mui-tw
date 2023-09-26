# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


#tailwind css
npm create vite@latest your-project-name -- --template react
cd food-app
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
"./index.html",
"./src/**/*.{js,ts,jsx,tsx}",
@tailwind base;
@tailwind components;
@tailwind utilities;

#mui
npm install @material-ui/core@"*" --legacy-peer-deps
npm install @material-ui/icons --legacy-peer-deps