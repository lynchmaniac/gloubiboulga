Gloubiboulga
=========

test de création d'un module npm pour échapper les caractères HTML

## Installation

  npm install gloubiboulga --save

## Usage

  var gloubiboulga = require('gloubiboulga')
      escape = gloubiboulga.escape,
      unescape = gloubiboulga.unescape;

  var html = '<h1>Hello World</h1>',
      escaped = escape(html),
      unescaped = unescape(escaped);

  console.log('html', html, 'escaped', escaped, 'unescaped', unescaped);

## Tests

  npm test

## Contributing

In lieu of a formal styleguide, take care to maintain the existing coding style.
Add unit tests for any new or changed functionality. Lint and test your code.

## Release History

* 0.1.0 Initial release