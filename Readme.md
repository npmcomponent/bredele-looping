*This repository is a mirror of the [component](http://component.io) module [bredele/looping](http://github.com/bredele/looping). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/bredele-looping`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# Looping

  Iteration utility made for **[datastore](http://github.com/bredele/datastore)**

## Installation

with component:

    $ component install bredele/looping

with nodejs:

    $ npm install looping

## API

You'll find lots of iteration components out there (like [component-each](https://github.com/component/each)). However, looping exposes a consistent API for both arrays and objects (the first argument is the object's key - or index for an array -).


### each(array, fn, [scope])

  Iterate an array:

```js
var each = require('looping');
each(['olivier', 'bredele'], function(key, val){
  //key is the array's index
})
```

### each(object, fn, [scope])

  Iterate an object;

```js
var each = require('looping');
each(conf, function(key, val){
  //key is the object's key
})
```


## License

  MIT
