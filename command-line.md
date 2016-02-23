# Running JavaScript on the command line

[Node.js](http://nodejs.org/) is an environment that lets you run JavaScript from the command line.

Let's say we have an `index.js` that looks like this:

```
console.log("ohai, Node JS!");
```

On the command line, we can enter "node index.js" to have Node run the file. The output would be:

```
ohai, Node JS!
```

## Modules

You might have noticed that if you keep all of your JavaScript in one file it can become messy quite quickly! When we want to split our JavaScript up into some smaller files, we can use **modules**.

Here are a few ways of doing modules.

* [Simple module](./1-simple-module);
* [Exporting an anonymous module](./2-export-anonymous);
* [Exporting a named module](./3-export-named).
