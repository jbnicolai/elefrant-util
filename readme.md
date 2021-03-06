# Elefrant Util

[![wercker status](https://app.wercker.com/status/abf296cb1fad2ac7c4f47e7eb56784c4/s/master "wercker status")](https://app.wercker.com/project/bykey/abf296cb1fad2ac7c4f47e7eb56784c4)

[![Dependency Status](https://gemnasium.com/Elefrant/elefrant-util.svg)](https://gemnasium.com/Elefrant/elefrant-util)

## Install

```sh
$ npm install --save elefrant-util
```


## Usage

Elefrant utils come with a bunch of basic libraries.

```js
var util = require('elefrant-util');

// Glob functions
var glob = util.glob;

// Lodash functions
var _ = util.lodash;

// Chalk functions
var chalk = util.chalk;

// Format functions
var format = util.format;

// Async functions
var async = util.async;
```

Be free to add new or extend libraries.


### format: `util.format`

Underscore.String [functions](https://github.com/epeli/underscore.string)

And, added new:

#### Filename

Extract the name from a file name.

```js
util.format.filename('util.js');
// Result: 'util'
```

#### Downlize

Get the value with a lower Case first character..

```js
util.format.downlize('ElefrantUtils');
// Result: 'elefrantUtils'
```

## License

MIT © [Elefrant](http://elefrant.com/#/license)
