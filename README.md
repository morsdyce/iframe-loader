# iframe-loader

A [webpack](https://webpack.github.io/) loader that creates an entry chunk for a file and loads it in an iframe.

## Installation

`npm install iframe-loader`

## Usage

```javascript
var childWindow = require('iframe?name=file-[hash].js!./file');
```
