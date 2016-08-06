# lunt-box-sizing
Global box model for the Lunt framework.

We are using here the box sizing `border-box` [inherited](https://css-tricks.com/inheriting-box-sizing-probably-slightly-better-best-practice/) approach.

## Installation

    npm install lunt-box-sizing --save

## Usage

You can use this component the way you want. It's just a Node.js module with a little bit of CSS.

### 1. In your CSS file

    @import "../node_modules/lunt-box-sizing/lunt-box-sizing.css"

You can also use [postcss-import](https://github.com/postcss/postcss-import) plugin to make it even easier.

### 2. In your Node.js modules

    var luntBoxSizing = require('lunt-box-sizing');
