## 📦 Minipack

> A simplified example of a modern module bundler written in JavaScript

#### (updated to Babel 7.0.0-rc.3)

### Introduction

As front-end developers, we spend a lot of time working with tools like [Webpack](https://github.com/webpack/webpack), [Browserify](https://github.com/browserify/browserify), and [Parcel](https://github.com/parcel-bundler/parcel).

Understanding how those tools work can help us make better decisions on how we write our code. By understanding how our code turns into a bundle and how that bundle looks like we can also debug it better.

The purpose of this project is to explain how most bundlers work under the hood. It contains a short implementation of a simplified but still reasonably accurate bundler. Along with the code, there are comments explaining what the code is trying to achieve.

### Cool, where do I start?

Head on to the source code: [src/minipack.js](src/minipack.js).

### Try running the code

Start by installing dependencies:

```sh
$ yarn install
```

And then run the script:

```sh
$ node src/minipack.js
```

```sh
$ yarn build
```

To lint:

```sh
$ yarn lint
```

### @babel/traverse:

The Babel Traverse module maintains the overall tree state, and is responsible for replacing, removing, and adding nodes

### @babel/parser:

The Babel parser (previously Babylon) is a JavaScript parser used in Babel.


### Additional links

- [babel-handbook](https://github.com/jamiebuilds/babel-handbook/blob/master/translations/en/plugin-handbook.md)

- [babel-traverse](https://babeljs.io/docs/en/next/babel-traverse.html)

- [babel-parser](https://babeljs.io/docs/en/next/babel-parser.html)

- [AST Explorer](https://astexplorer.net)
- [Babel REPL](https://babeljs.io/repl)
- [Babylon](https://github.com/babel/babel/tree/master/packages/babel-parser)
- [Babel Plugin Handbook](https://github.com/thejameskyle/babel-handbook/blob/master/translations/en/plugin-handbook.md)
- [Webpack: Modules](https://webpack.js.org/concepts/modules)

### Read this in other languages

- [한글/Korean](https://github.com/hg-pyun/minipack-kr)
- [中文/Chinese](https://github.com/chinanf-boy/minipack-explain)
- [Русский/Russian](https://github.com/makewebme/build-your-own-webpack)
