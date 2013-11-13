
# is-key

  determine if a particular key was pressed in an event handler

## Installation

  Install with [component(1)](http://component.io):

    $ component install bmcmahen/is-key

## Usage

```javascript
var key = require('is-key');
el.onkeyup = function(e){
  if (key(e, ['i', 'b', 'shift', 'command'])){
    console.log('its one of those');
  }
}
```


## License

  MIT
