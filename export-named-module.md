# Exporting a named module

```JavaScript
// named.js
exports.named = function () {
  console.log('Hello, named!');
}

// app.js
var named = require('./named.js').named;
named();
```
