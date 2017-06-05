## three-ply-loader
> NodeJS wrapper for Three.js' PLYLoader function

### Install

```
$ npm install --save three-ply-loader
```

### Usage

```javascript
const THREE = require('three');
const PLYLoader = require('three-ply-loader');
PLYLoader(THREE);

console.log(typeof THREE.PLYLoader);
//=> 'function'
```

### License
MIT