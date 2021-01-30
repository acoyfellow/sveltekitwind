node v12.18.4
npm v6.14.6
---
npm init svelte@next sveltekitwind
cd sveltekitwind
npm i
npm run dev

npm i @snowpack/plugin-build-script postcss postcss-cli postcss-load-config tailwindcss autoprefixer -D

touch postcss.config.js

touch src/routes/global.pcss