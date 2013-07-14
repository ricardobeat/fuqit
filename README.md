fuqzed
=======

    npm install -g fuqzed

Node.js port of the [fuqit](https://github.com/zedshaw/fuqit) library, a stupid simple web "framework". Drop files into a directory and everything just works (shouts out to PHP).

Files are either a `.js` module exporting a `function (req, res)` or an [EJS](http://github.com/visionmedia/ejs) template (`.js|html`). Everything else is served as a static file.

Just `fuqzed` inside your target directory. See `/example`.

    fuqzed [port]

![](http://f.cl.ly/items/1O0J043n0s3P0N0t210J/fuq.png)

#### Local install

If you want to keep `fuqzed` local to your project:

    npm install fuqzed
    ./node_modules/.bin/fuqzed

Or add `scripts: { "fuqzed": "fuqzed" }` to your `package.json` and use `npm run-script fuqzed`.

#### License

[MIT](http://ricardo.mit-license.org)
