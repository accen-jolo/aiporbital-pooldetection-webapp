## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production
To deploy to Azure Static Web Apps:
```
//instructions go here
```

To deploy to Github Pages:
```sh
npm run build
git add dist
git commit -m "deploy"
git subtree push --prefix dist origin gh-pages
```

For it to run in Github pages, ensure that:
1. "build": "vite build --base=/aiporbital-pooldetection-webapp/", is found in package.json
2. base: process.env.NODE_ENV === "production" ? "/REPO/" : "./", is found in vite.config.js
