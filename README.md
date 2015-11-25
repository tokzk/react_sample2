# WEB+DB Vol.87 Emerging Web Technology 研究室 第13回

Flux(Fluxxor)を導入したカウントの実装

## Reactの準備

```shell
$ npm install react
$ npm install react-dom
$ npm install fluxxor
```

## トランスパイラの準備

```shell
$ npm install -g browserify
$ npm install -g watchify
$ npm install reactify

$ watchify -t reactify src/app.jsx -o dest/app.js -v
```

