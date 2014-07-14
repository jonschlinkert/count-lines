# count-lines [![NPM version](https://badge.fury.io/js/count-lines.png)](http://badge.fury.io/js/count-lines)

> Count the lines in a string, works with windows carriage returns or unix style newlines.

## Install
#### [npm](npmjs.org)

```bash
npm i count-lines --save
```

## Usage

```js
var count = require('count-lines');
console.log(count('a\nb\nc'));
//=> '3'

console.log(count('a\r\nb\r\nc'));
//=> '3'
```

## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

## License
Copyright (c) 2014 Jon Schlinkert, contributors.  
Released under the MIT license

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on July 13, 2014._