# BoilerPlateCode_ReactJS_Vite_TailwindCSS

Boiler Plate Code - React JS+ Vite + tailwind css

1. Terminal -> npm create vite@latest quiz_riddle_react -- --template react

	Or

1. Terminal -> npm create vite@latest my-project
2. cd my-project
3. Terminal -> npm install -D tailwindcss postcss autoprefixer
4. Terminal -> npx tailwindcss init -p
5. tailwind.config.js file -> 
    1. /** @type {import('tailwindcss').Config} */
    2. export default {
    3. content: [
    4. "./index.html",
    5. "./src/**/*.{js,ts,jsx,tsx}",
    6. ],
    7. theme: {
    8. extend: {},
    9. },
    10. plugins: [],
    11. }
6. Index.css file ->
    1. @tailwind base;
    2. @tailwind components;
    3. @tailwind utilities;
7. Terminal -> npm run dev
8. netlify.toml file -> 
    1. [build]
    2. base    = ""
    3. publish = "dist/"
    4. command = "vite build"
    5. [[redirects]]
    6. from = "/*"
    7. to = "/index.html"
    8. status = 200
9. Create .env file
10. Create .env.sample file
11. Create .nvmrc file -> 20.8.0
12. Create .gitignore file ->
    1. # Logs
    2. logs
    3. *.log
    4. npm-debug.log*
    5. yarn-debug.log*
    6. yarn-error.log*
    7. pnpm-debug.log*
    8. lerna-debug.log*
    9. node_modules
    10. dist
    11. dist-ssr
    12. *.local
    13. # dotenv environment variables file
    14. .env
    15. .env.test
    16. .env.production
    17. # Editor directories and files
    18. .vscode/*
    19. !.vscode/extensions.json
    20. .idea
    21. .DS_Store
    22. *.suo
    23. *.ntvs*
    24. *.njsproj
    25. *.sln
    26. *.sw?
13. Terminal -> npm i @reduxjs/toolkit axios js-cookie react-hook-form react-redux react-router-dom redux-thunk
14. Create folders of Components, Auth, Functions, Pages, Redux-Store
15. Configure App.jsx and Main.jsx files.
16. App.css ->  Comment max-width and padding
