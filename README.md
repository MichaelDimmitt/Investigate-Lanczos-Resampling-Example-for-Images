## Spike-investigate-resampling-resizing-compression-for-images-react

## Helpful Starting Places:
https://github.com/sorrycc/awesome-javascript#image-processing
<br/>https://github.com/brillout/awesome-react-components

https://js.libhunt.com/
<br/>https://nodejs.libhunt.com/
<br/>https://react.libhunt.com/

https://www.npmjs.com/search?ranking=popularity&q=compress
<br/>https://www.npmjs.com/search?q=image&ranking=popularity
<br/>https://react.libhunt.com/categories/5557-image-editing


## Best current candidates are at the top, get me to the console.log()
```bash
npm install downscale
npm install sharp &&
npm install cropperjs &&
npm install jimp &&
npm install lwip &&
npm install pica &&
npm install @rgba-image/lanczos &&
npm install ee-image-worker &&
npm install wasm-imagemagick &&
cp node_modules/wasm-imagemagick/dist/magick.wasm public &&
cp node_modules/wasm-imagemagick/dist/magick.js public
```
Stack Overflow custom solution: https://stackoverflow.com/questions/2303690/resizing-an-image-in-an-html5-canvas/3223466#3223466

```javscript
var downscale = require('downscale');
const sharp = require('sharp');
const Cropper = require('cropperjs'); // import Cropper from 'cropperjs';
var Jimp = require('jimp');
var lwip = require('lwip');
const pica = require('pica')();
const { lanczos } = require( '@rgba-image/lanczos' )
var eeImage = require('ee-image-worker');
import { buildInputFile, execute } from 'wasm-imagemagick'

console.log({downscale, sharp, Cropper, Jimp, lwip, pica, lanczos, eeImage, buildInputFile})
```

Additional Notes:
```javascript
// npm install image-size --save
// var sizeOf = require('image-size');
// var dimensions = sizeOf('images/funny-cats.png');

// https://www.npmjs.com/package/image
// var Image = require('image');
// var png = new Image('png').encodeSync(buffer, width, height);
```

## Usage
coming soon.
