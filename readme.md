# strip-path [![Build Status](https://travis-ci.org/sindresorhus/strip-path.svg?branch=master)](https://travis-ci.org/sindresorhus/strip-path)

> Strip a path from a path


## Install

```bash
$ npm install --save strip-path
```


## Usage

```js
var stripPath = require('strip-path');

stripPath('path1/path2/path3/path4', 'path1/path2');
//=> 'path3/path4'
```


## API

### stripPath(path, stripPath)

#### path

*Required*  
Type: `String`  

The path to stripped.

#### stripPath

*Required*  
Type: `String`  

The path to strip from `path`.


## License

[MIT](http://opensource.org/licenses/MIT) © [Sindre Sorhus](http://sindresorhus.com)
