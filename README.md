# tv-maze

## Usage

``` js

var tvmaze = require('tv-maze')
var client = tvmaze.createCliente()

client.shows(function (err, shows) {
	// do something shows
})

client.search('lost', function (err, shows) {
	// do something shows
})

```
