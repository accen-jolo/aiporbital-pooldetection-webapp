## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
git add dist
git commit -m "deploy"
git subtree push --prefix dist origin gh-pages
```
