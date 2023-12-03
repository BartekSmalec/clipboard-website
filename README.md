# clipboard-website

* `nvm use 20.6.1` <br />
* Also set Node version in Language&Framework to 20.6.1
* `npm init -y` <br />
* `npm install tailwindcss@latest` <br />
* `npx tailwindcss init`
* add config to tailwind.config.js
`
  content: ["./src/**/*.{html,js}"]`
* add build script to package.json <br />
* `"build": "tailwindcss -i ./src/style.css -o ./public/style.css --watch"`
* Create src/style.css and add
* `@tailwind base;
  @tailwind components;
  @tailwind utilities;`
* `npm run build`

![screencapture-localhost-63342-clipboard-website-public-index-html-2023-12-03-23_06_06.png](screenshots%2Fscreencapture-localhost-63342-clipboard-website-public-index-html-2023-12-03-23_06_06.png)
![screencapture-localhost-63342-clipboard-website-public-index-html-2023-12-03-23_06_58.png](screenshots%2Fscreencapture-localhost-63342-clipboard-website-public-index-html-2023-12-03-23_06_58.png)