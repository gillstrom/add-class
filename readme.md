# add-class

> Add a given class to elements.


## Install

```
$ npm install --save add-class
```


## Usage

```js
var addClass = require('add-class');
var el = document.querySelector('div');
var els = document.querySelectorAll('span');

addClass(el, 'foo');
addClass(els, 'bar');
```


## Browser API

### addClass(element, className)

#### element

*Required*  
Type: HTML DOM element

Element(s) to add class to.

#### className

*Required*  
Type: `string`

Class name to be added.


## Related

* [has-class](https://github.com/gillstrom/has-class) - Check if an element has a given class.


## License

MIT © [Andreas Gillström](http://github.com/gillstrom)
