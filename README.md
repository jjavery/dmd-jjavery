# dmd-jjavery
Plugin for [jsdoc2md](https://github.com/jsdoc2md/jsdoc-to-markdown) to produce markdown suitable for API documentation.

## Install and use
In the project requiring this plug-in, install it as a devDependency:
```
$ npm install @jjavery/dmd-jjavery --save-dev
```

Then pass the plug-in name to `jsdoc2md` or `dmd` when generating your docs:
```
$ jsdoc2md --plugin @jjavery/dmd-jjavery --files src/*.js
```

* * *

&copy; 2015-16 Lloyd Brookes <75pound@gmail.com>.
