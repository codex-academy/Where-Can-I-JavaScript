---
layout: default
title: Running JavaScript on the command line
---

# Running JavaScript on the command line

[Node.js](http://nodejs.org/) is an environment that lets you run JavaScript from the command line. Check that you have Node installed (and what version you have) by running

```bash
node -v
```

## Node and the console

Let's say we have an `index.js` that looks like this:

```javascript
// index.js
var greet = "Node Js";
console.log("ohai, " + greet + "! :)");
```

On the command line, we can enter `node index.js` to have Node run the file.

```bash
// the command line
$ node index.js
ohai, Node JS! :)
```

## Modules

You might have noticed that if you keep all of your JavaScript in one file it can become messy quite quickly! When we want to split our JavaScript up into some smaller files, we can use **modules**.

Make a new repository called "Where Can I JavaScript?" and put the new bits of work in there. You'll need to `git init` and to add a new repository on GitHub that's linked to your local one.

Here are a few ways of doing modules.

* [Simple module](./simple-module.html);
* [Exporting an anonymous module](./export-anonymous-module.html);
* [Exporting a named module](./export-named-module.html).

---

Last but not least, you can also [run JavaScript in a robot](robots.html).
