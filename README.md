## React set up :
---
### create project : to install react  with folder:

```Bash
npm create vite@latest my-react-app --template react
```

## to install react without react :

```Bash
npm create vite
```
---

## after install :
---
### to install node module :
```Bash
npm i
or
npm install
```

### run in the local host :

```Bash
npm run dev
or 
npx vite 
```

---

# Vs Code extension for react :
---

1. auto close tag.
2. auto import -es6,ts,jsx,tsx.
3. auto rename tag.
4. EsLint.
5. npm intellisense.
6. path intellisense.
7. postman.
8. prettier.
9. react.js code snippets.
10. snap code
11. stylelint.
12. tailwindcss intellisense.
13. thunder client / postman
14. vsCode react refactor.
15. vscode-icons.

---

## Install Tailwind CSS :
---
```Tailwind css
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

## Configure your template paths :

---
Add the paths to all of your template files in your `tailwind.config.js` file.

```tailwind.config.js
/** @type {import('tailwindcss').Config} */ 

export default {
content: [ "./index.html",
"./src/**/*.{js,ts,jsx,tsx}",
],
theme: { extend: {}, 
},
plugins: [],
}

```

## Add the Tailwind directives to your CSS :
---
```index.css

@tailwind base;
@tailwind components;
@tailwind utilities;

```
