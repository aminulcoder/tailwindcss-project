1. npm init -y
2. npm install -D tailwindcss postcss autoprefixer vite
3.npx tailwindcss init -p
4.Create a folder css then create a file main.css
5.tailwind.config.js file =========== content: ["*"],
6.package.json   
"scripts": {
    "dev": "vite"
  },

  7.css folder then main.css file and paste it are given below

  @tailwind base;
  @tailwind components;
  @tailwind utilities;

8. main.css file link into  index.html file

9.and run it this project 
npm run dev