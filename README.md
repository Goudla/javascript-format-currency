# to-dollars
A JavaScript utility function from formatting numbers as dollars

### Installation

In a browser:
```html
<script src="index.js"></script>
```

Using [npm](https://www.npmjs.com/):

    $ npm install --save javascript-array-search

Or [yarn](https://yarnpkg.com/):

    $ yarn add javascript-array-search

In Node.js:
```js
var toDollars = require('to-dollars');
```

### Example
```js
toDollars(0)
//=> $0.00

toDollars(0.009)
//=> $0.01

toDollars(1000000000)
//=> $1,000,000,000.00

toDollars('hello world')
// => undefined

toDollars('1234')
// => $1,234.00
```
