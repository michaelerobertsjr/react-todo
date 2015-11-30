# Todo App using React w/ Redux

### Build process:

```sh
npm install -g babel-cli
npm install -g babel-plugin-transform-react-jsx
npm build
```

### Run:

View index.html with a server or webstorm preview mode.

### npm build includes:
```sh
babel --plugins transform-react-jsx script.jsx > pre-script.jsx
babel pre-script.jsx --out-file script-compiled.js
```