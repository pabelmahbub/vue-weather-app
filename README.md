### vue-weather-app
### Live site: https://vue-weather-app-9.netlify.app/

How to run it in local:
```
a. clone repo: https://github.com/pabelmahbub/vue-weather-app.git
b. npm i
c. npm run dev
```
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
Package.json:
```
"dependencies": {
    "axios": "^1.4.0",
    "uid": "^2.0.2",
    "vue": "^3.2.47",
    "vue-router": "^4.1.6"
  },
  "devDependencies": {
    "@vitejs/plugin-vue": "^4.0.0",
    "autoprefixer": "^10.4.14",
    "postcss": "^8.4.23",
    "tailwindcss": "^3.3.2",
    "vite": "^4.1.4"
  }
  ```
