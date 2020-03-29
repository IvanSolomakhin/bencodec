[![build](https://circleci.com/gh/IvanSolomakhin/bencodec.svg?style=shield)](https://app.circleci.com/pipelines/github/IvanSolomakhin/bencodec)
[![codecov](https://codecov.io/gh/IvanSolomakhin/bencodec/branch/master/graph/badge.svg)](https://codecov.io/gh/IvanSolomakhin/bencodec)

## bencodec
  Bencode codec. Fast, easy to use, without dependencies.

## Installation
  ```
  npm install bencodec --save
  ```
  
## Usage
  ```js
  const bencodec = require('bencodec');  
    
  // decode example  
  const decoded = bencodec.decode('d3:bar4:spam3:fooi42ee');  
  
  // encode number  
  const encoded = bencodec.encode(42);  
  // encode string  
  const encoded = bencodec.encode('spam');  
  // encode Array  
  const encoded = bencodec.encode(['spam', 42]);  
  // encode Object  
  const encoded = bencodec.encode({ bar: 'spam', foo: 42 });  
  ```
  
  Check [Wiki](https://github.com/IvanSolomakhin/bencodec/wiki) for more information. 
  

## Tests
  ```
  npm test
  ```
