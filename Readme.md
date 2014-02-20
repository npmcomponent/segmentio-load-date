*This repository is a mirror of the [component](http://component.io) module [segmentio/load-date](http://github.com/segmentio/load-date). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/segmentio-load-date`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# load-script

  Returns the Date the page started loading, with a "good enough" version for browsers without `performance.timing`.

## Installation

    $ component install segmentio/load-date

## Example
    
```js
var date = require('load-date');
date.toString(); // "Wed Mar 06 2013 15:26:40 GMT-0800 (PST)"
```

## License

  MIT
