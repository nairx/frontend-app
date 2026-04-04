npm install -D tailwindcss@3 postcss autoprefixer
npx tailwindcss init -p
Add following in index.css
@tailwind base;
@tailwind components;
@tailwind utilities;
in tailwind.config.js update following
  content: ["./index.html", "./src/**/*.{js,ts,jsx,tsx}"],