*This repository is a mirror of the [component](http://component.io) module [yields/prevent](http://github.com/yields/prevent). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-prevent`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# prevent

  Cross-browser preventDefault

## Installation

    $ component install yields/prevent

## Example

```js
anchor.onclick = require('prevent');
anchor.onclick = function(e){
  if (something) return require('prevent')(e);
};
```

## API

### prevent(e)

  Prevent the given `e`, if the argument is omitted,
  the method will fallback to `window.event`.

## License

  MIT
