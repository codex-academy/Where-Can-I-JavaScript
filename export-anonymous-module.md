# Exporting an anonymous module

```JavaScript
// eam.js
module.exports = function () {
  console.log('Hello, eam!');
}

// app.js
var eam = require('./eam.js');
eam();
```
