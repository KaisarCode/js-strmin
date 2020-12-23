# STRMin
[js] Simple minify (Remove new lines and multiple spaces).

### Install
```
npm install kc-strmin
```

### Use
```js
var strmin = require('kc-strmin');
var str = strmin(`
Hello      world

This   is my  

content.
`);
console.log(str);
```
