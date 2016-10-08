Spreefang Frontend starter kit
=========================

Frontend starter/bootstrapper kit with Webpack, React&Redux and Typescript

React and Webpack part inspiration:
https://www.typescriptlang.org/docs/handbook/react-&-webpack.html

## Getting started

Run `npm install`

Note: You *should* have installed `webpack` and `typings` globally

Then install typings for react and redux with:
```bash
$ typings install --global --save dt~react
$ typings install --global --save dt~react-dom
$ typings install --global --save dt~redux
$ typings install --global --save dt~react-redux 
```

todo: add instructions about running webpack-dev-server

## Working with the code

You can build the code once with the following command
```bash
$ webpack
```

Alternatively you can use webpack with the watcher flag
```back
$ webpack --watch
```
