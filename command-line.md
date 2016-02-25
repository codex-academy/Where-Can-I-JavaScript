# Running JavaScript on the command line

[Node.js](http://nodejs.org/) is an environment that lets you run JavaScript from the command line. Check that you have Node installed (and what version you have) by running

```
node -v
```

## Node and the console

Let's say we have an `index.js` that looks like this:

```JavaScript
// index.js
var greet = "Node Js";
console.log("ohai, " + greet + "! :)");
```

On the command line, we can enter `node index.js` to have Node run the file. The output would be:

```
// the command line
$ node index.js
ohai, Node JS! :)
```

## Modules

You might have noticed that if you keep all of your JavaScript in one file it can become messy quite quickly! When we want to split our JavaScript up into some smaller files, we can use **modules**.

Here are a few ways of doing modules.

* [Simple module](./1-simple-module);
* [Exporting an anonymous module](./2-export-anonymous-module);
* [Exporting a named module](./3-export-named-module).

---

Last but not least, you can also [run JavaScript in a robot](robots.md).
