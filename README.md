# Nextjs 15 Prettier Eslint Husky Setting 

1. npx create-next-app@latest
2. npm i -D eslint@8.57.0 eslint-config-next eslint-config-prettier eslint-plugin-tailwindcss eslint-plugin
   -unused-imports @typescript-eslint/parser
3. npm i -D prettier @ianvs/prettier-plugin-sort-imports prettier-plugin-tailwindcss

--- Husky Setting ---

1. npm install --save-dev husky
2. npm pkg set scripts.prepare="husky install"
3. npm run prepare

**Requires an eslint 9 upgrade at a later date**
