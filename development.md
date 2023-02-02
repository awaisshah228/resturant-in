
# Resturant
## Client Setup
npx create-react-app client --template typescript  
npm i react-router-dom
### Tailwind Setup
npm install -D tailwindcss  
npx tailwindcss init

 put in tailwind.config.js  
`/** @type {import('tailwindcss').Config} */  
module.exports = {  
   content: ["./src/**/*.{js,jsx,ts,tsx}"],    
   theme: {  
    extend: {},  
  },  
  plugins: [],  
}`  

npm i react-helmet-async  



