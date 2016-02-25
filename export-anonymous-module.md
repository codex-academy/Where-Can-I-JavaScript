# Exporting an anonymous module

```JavaScript
// anonymous.js
module.exports = function () {
  console.log('Hello, anonymous!');
}

// app.js
var anonymous = require('./anonymous.js');
anonymous();
```
