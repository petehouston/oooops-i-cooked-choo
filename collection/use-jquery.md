# Use jQuery

If you want to use jQuery in `choo` app, first need to install jQuery from command line:

```sh
$ npm install jquery
```

and inside your app, include the library with reference to global object.

```js
var $ = require('jquery');
window.$ = window.jQuery = $;
```

*P/S: I think it is okay for current state of `choo`. However, still need to look for a better `choo` build alternative. I prefer the webpack way to reference external libraries.*