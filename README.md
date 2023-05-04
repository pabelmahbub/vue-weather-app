### vue-weather-app
### Live site: https://vue-weather-app-9.netlify.app/

#### clone from repo -> npm i -> npm run dev
How to develop a vue app:
```
a. create a folder named vue-weather-app
b. cd vue-weather-app
c. npm init vue@latest
d. npm run dev
```
Installation of Tailwind:
```
a. npm i -D tailwindcss postcss autoprefixer
b. npx tailwind init -p 
c. Inside tailwind.config.js
content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
d. create a css file in src/assets named tailwind.css and add:
@tailwind base;
@tailwind components;
@tailwind utilities;
e. import tailwind.css in main.js file:
import "./assets/tailwind.css";
```
