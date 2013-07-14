fuqit.js
=========

    npm install -g fuqit

Node.js port of the [fuqit](https://github.com/zedshaw/fuqit) library, a stupid simple web "framework". Drop files into a directory and everything just works (shouts out to PHP).

Files are either a `.js` module exporting a `function (req, res)` or an [EJS](http://github.com/visionmedia/ejs) template (`.js|html`). Everything else is served as a static file.

Just `fuqit` inside your target directory. See `/example`.

    fuqit [port]

![](http://f.cl.ly/items/1O0J043n0s3P0N0t210J/fuq.png)

#### Local install

If you want to keep `fuqit` local to your project:

    npm install fuqit
    ./node_modules/.bin/fuqit

Or add `scripts: { "fuqit": "fuqit" }` to your `package.json` and use `npm run-script fuqit`.

#### License

[MIT](http://ricardo.mit-license.org)
