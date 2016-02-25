# Exporting an anonymous module

Here's an example of exporting an anonymous (no name!) function.

```JavaScript
// eam.js
module.exports = function () {
  console.log('Hello, eam!');
}

// app2.js
var eam = require('./eam.js');
eam();
```

1. Create the two files above and then run `node app2.js` in the terminal. What do you see?
2. Update `eam.js` with some of your own code.
3. What happens if you add another `module.exports` after the first one?
