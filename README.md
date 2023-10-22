# AI-Pacman Project Series

## Overview

This project, is inspired from [Build a Modern Login/Signup Form with Tailwind CSS and React](https://www.loginradius.com/blog/engineering/guest-post/modern-login-signup-form-tailwindcss-react/)

## Steps did in this project :

### 

npx create-react-app react-tailwind-app

cd react-tailwind-app

npm i react-router-dom

npm install -D tailwindcss postcss autoprefixer

npx tailwindcss init -p

add this to your tailwind.config.js

content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],

add this to your index.css at the root level

@tailwind base;
@tailwind components;
@tailwind utilities;

it may show error but you need to install this plugin in the vscode to resolve it.

PostCSS Langauge Support by Syntax highlighting for modern and experimental css in VsCode.

npm start

## Project Struture is :

.
├── components/
│   ├── FormAction.js
│   ├── FormExtra.js
│   ├── Header.js
│   ├── Input.js
│   ├── Login.js
│   └── Signup.js
├── constants/
│   └── formFields.js
└── pages/
    ├── Login.js
    └── Signup.js




### Happy Coding!

---

**Note:** This is a dupliaction of what it is done in the link shown as a practice towards the Tailwind Css.
