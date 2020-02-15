# Custom babel configuration (pug to react)

##### Dependencies

```
$ npm i -g @babel/cli @babel/core prettier babel-plugin-transform-react-pug
```

##### Command

```
$ babel --no-babelrc src/ --out-dir src/ --extensions .pjs --plugins="$(npm -g root)/babel-plugin-transform-react-pug" && prettier --write "src/**/*.js"
```
