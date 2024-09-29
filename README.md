
![Screenshot 2024-09-29 at 13 38 37](https://github.com/user-attachments/assets/b2278b37-2816-4221-bf54-c67b599ae35b) ![Screenshot 2024-09-29 at 13 38 55](https://github.com/user-attachments/assets/45aebcc2-afae-4de3-9dc6-0117bc919b0e) ![Screenshot 2024-09-29 at 13 39 14](https://github.com/user-attachments/assets/3070285b-ea27-472c-a673-2cea04e7c67e) ![Screenshot 2024-09-29 at 13 39 26](https://github.com/user-attachments/assets/d0f6fe8d-6dda-4b98-a82f-56789008d355) ![Screenshot 2024-09-29 at 13 40 03](https://github.com/user-attachments/assets/70048532-506c-4e1e-9e45-670c4fe5524f)

## Marketing-TailwindCSS-Templet

Marketing-TailwindCSS-Templet is a Static React-Vite Frontend Landing Page, using React-Vite, TailwindCSS, Framer-Motion, React-Animate, React-Icons, and deployed on Netlify.

**Note: To check this web app live, click here:** https://marketing-arnob.netlify.app

## To Install Dependencies

Before you launch this web application, please make sure to install all required dependencies, which are listed in the package.json file.

To install all dependencies, run this command from your project folder: `npm install`

## To Install NodeJS

Make sure you have NodeJS installed on your machine first, The installation instructions are here: https://nodejs.org/en/

Run your project: `npm run dev`

Run on your browser Local: `http://localhost:5173/`

## To Create TailwindCSS React Vite Project

Open up your terminal and bootstrap a new React Vite App by: `npm create vite@latest my-project -- --template react`

Then go to that project folder, and write this command via terminal from your project folder: `npm install -D tailwindcss postcss autoprefixer`

Then install tailwindcss and its peer dependencies, then generate your `tailwind.config.js` and `postcss.config.js` files: `npx tailwindcss init -p`

Then add the paths to all your template files in your tailwind.config.js file.

```
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

Then add the @tailwind directives for each of Tailwind’s layers to your ./src/index.css file.

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Run your project: `npm run dev`

Run on your browser Local: `http://localhost:5173/`

(For more details, visit: https://tailwindcss.com/docs/guides/vite )

## React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

