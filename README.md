# phantomjs-polyfill-string-includes

This is a polyfill for String.prototype.includes which is missing from PhantomJS.


## Installation

```
    npm install --save-dev phantomjs-polyfill-string-includes
```

## Usage with Karma

Include the polyfill directly in the files list of your karma.conf

```
    ...
    files: [
      './node_modules/phantomjs-polyfill-string-includes/index.js',
      ...
    ]
    ...
```
