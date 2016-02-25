# Exporting a named module

```JavaScript
// myfancyname.js
exports.myfancymethod = function () {
  console.log('Hello, myfancyname!');
}

// app3.js
var myfancyname = require('./myfancyname.js');
myfancyname.myfancymethod();
```

1. Create the two files above and then run `node app3.js` in the terminal. What do you see?
2. Update `myfancyname.js` with some of your own code inside `myfancymethod`.
3. Add another `exports`: `myotherfancymethod` with some of your own code inside.
