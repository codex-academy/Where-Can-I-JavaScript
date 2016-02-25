# Exporting a named module

```JavaScript
// myfancyname.js
exports.myfancymethod = function () {
  console.log('Hello, myfancyname!');
}

// app.js
var myfancyname = require('./myfancyname.js');
myfancyname.myfancymethod();
```
