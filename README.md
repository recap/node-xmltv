# xmltv

A xmltv reader based on sax.

## Getting Started
Install the module with: `npm install xmltv` It's not yet in npm though !

```javascript
var xmltv = require('xmltv');
xmltv.on("programme", function(programme) {
  //Do something with programmes one by one as they are parsed
});
xmltv.parseFile("tvguide.xml");
```

## Documentation
_(Coming soon)_

## Examples
_(Coming soon)_

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).

## Release History
_(Nothing yet)_

## License
Copyright (c) 2013 Lionel Martin  
Licensed under the MIT license.
