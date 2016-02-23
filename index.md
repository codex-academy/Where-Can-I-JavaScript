# Where Can I JavaScript?

There are lots of places to **write** and to **run** JavaScript.

We almost always **write JavaScript** in our editor (Atom or Sublime).

## Running JavaScript in the browser

The first place we see JavaScript running is in the browser. Most web sites you visit use JavaScript to add behaviour or funky interactions to the page. The browser loads an HTML page. Inside there somewhere will be a `script` tag, probably like this:

```
<script src="app.js"></script>
```

Once the browser has downloaded `app.js`, it executes it.

## Running JavaScript in the browser console

Open your browser's Dev Tools, and select the **Console** tab. If you've used any `console.log` statements in `app.js`, this is where they'll appear.

You can also write and run JavaScript here, like this:

![](img/browser-console.png)

The console `return`s something every time you hit Enter. You can even `console.log` here!

## Running JavaScript in JS Bin

[JS Bin](https://jsbin.com/) is a web development debugging tool. It's a bit of a mash up of the insides of a browser and an online editor. It gives you a playground for HTML, CSS, JavaScript, the Console, and the rendered web page Output.

Here you can write JavaScript in the **JavaScript** tab or in the **Console** tab, and see the output in the Console tab or the Output tab (depending on what you write).
