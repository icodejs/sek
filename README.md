# sek
Tiny millisecond helper

## Getting Started
Install the Sek NPM module and save it to your package.json file as a dependency:

```
$ npm install sek --save
```

## Usage
```javascript
var sek = require('sek');

sek(5) // 5000 milliseconds

setInterval(() => {
  // do something every 5 seconds
}, sek(5));
```
