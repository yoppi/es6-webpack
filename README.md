# ES6 + babel(babel-loader) + webpack Demo

requirements:

* babel(+babel-loader)
* webpack

## setup

```
$ npm install -g babel
$ npm install babel-loader --save-dev
$ npm install -g webpack
```

## build

```
$ webpack
```

or watching directory to build on the fly.

```
$ webpack --watch
```

## run

You can access directory `index.html` on browser, or use `simple-httpserver`.

https://github.com/yoppi/simple-httpserver

```
$ simple-httpserver
Serving HTTP on localhost port 8000
```

then, access `localhost:8000`.
