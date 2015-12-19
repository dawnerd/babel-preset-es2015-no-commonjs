# babel-preset-es2015-no-commonjs

> Babel preset for all es2015 plugins except commonjs.

## Install

```sh
$ npm install --save-dev babel-preset-es2015-no-commonjs
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es2015-no-commonjs"]
}
```

### Via CLI

```sh
$ babel script.js --presets es2015-no-commonjs
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["es2015-no-commonjs"]
});
```
