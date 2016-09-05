# node-image-base64

Nodejs module for convert image to base64 (blob, canvas)

## Install

```bash
npm install node-image-base64
```

## Example

```javascript
var convert = require('node-image-base64'),
getBase64ImageBlob = convert.getBase64ImageBlob,
getBase64ImageCanvas = convert.getBase64ImageCanvas;

var url = 'http://lorempixel.com/400/200/';

getBase64ImageBlob(url, function(base64)  {
  console.log(base64);
});

getBase64ImageCanvas(url, function(base64)  {
  console.log(base64);
});
```

## License

MIT
