# clipboard-website

# tailwind-mini

* `nvm use 20.6.1` <br />
* Also set Node version in Language&Framewordk to 20.6.1
* `npm init -y` <br />
* `npm install tailwindcss@latest` <br />
* `npx tailwindcss init`
* add config to tailwind.config.js
`
  content: ["./src/**/*.{html,js}"]`
* add build script to package.json <br />
* `"build": "tailwindcss -i ./src/style.css -o ./dist/style.css --watch"`
* Create src/style.css and add
* `@tailwind base;
  @tailwind components;
  @tailwind utilities;`
* `npm run build`