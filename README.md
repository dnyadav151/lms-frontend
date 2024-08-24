# LMS FRONTEND

### Set up Instructions
```
    1. create the Project
    npm create vite@latest
    2. move into the repo
    cd lms-frontend
    3. Install Dependencies
    npm install
    4. Run the Server
    npm rum dev
    5. Setting up Tailwind
    -> npm install -D tailwindcss postcss autoprefixer // installing tailwind
    -> npx tailwindcss init //creates tailwind.config.js file
    -> add file extensions to tailwind config file : "./src/**/*.{html,js}","./index.html"
    -> Add the @tailwind directives at the top of index.css file: 
       @tailwind base;
       @tailwind components;
       @tailwind utilities;
    6. Installing plugins and dependencies
       npm i @reduxjs/toolkit react-redux react-router-dom react-icons react-chartjs-2 chart.js daisyui@latest axios react-hot-toast @tailwindcss/line-clamp 

```