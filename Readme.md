*This repository is a mirror of the [component](http://component.io) module [jkroso/classes](http://github.com/jkroso/classes). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/jkroso-classes`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# classes

  x-browser class manipulation

## Installation

_With [packin](//github.com/jkroso/packin) or [component](//github.com/component/component)_

	$ packin add jkroso/classes

then in your app:

```js
var classes = require('classes')
```

## API

### add(name, el)

  Add class `name` if not already present.

### remove(name, el)

  Remove `name` if present. If name is a `RegExp` it will act like `removeMatching()`.

### removeMatching(re, el)

  Remove all classes matching `re`.

### toggle(name, el)

  Toggle class `name`.

### array(el)

  Return an array of classes.

## Running the tests

Just run `make` and navigate your browser to the test directory.

## Thanks

This is very heavily based off [component/classes](//github.com/component/classes) test suite and all. This is just a port to a function based API rather than a Method based one.