# Guide

--> npm create vite@latest

choose project name : client 

go to tailwind css vite react guide ...

npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

-------------------------------------------------------
in tailwind.config.js

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

-----------------------------------------------------------------

index.css

@tailwind base;
@tailwind components;
@tailwind utilities;

------------------------------------------------------------------


and start app with command 

npm run dev


----------------------------------------------------------------


--> Create pages and routes

src -> pages -->

About
SignIn
SignUp
Dashboard
Home
Projects



-------------------
to create pakage.json file command - npm init -y








----------------------------------------
//Packages npm i

react-router-dom



