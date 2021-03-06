# ods2json

 [![npm version](https://badge.fury.io/js/ods2json.svg)](https://www.npmjs.com/package/ods2json) [![Dependency Status](https://david-dm.org/Infostroy/ods2json.svg)](https://david-dm.org/Infostroy/ods2json)

## Installation

	npm install ods2json

## Features

  * Document styles exporting
  * All formulas exported and available for use
  * Simple JSON structure
  * Cell data types and graphical contents exporting
  * Media (charts, images, music, videos) exporting

## Usage

Export into file

```js
var conv = require('ods2json');
c = new conv;
c.convert('sheet.ods', 'parsed.json');
```

or into stdout

```js
var conv = require('ods2json');
c = new conv;
var json = c.convert('sheet.ods', false, true);
```

## License 

The MIT License (MIT)

Copyright (c) Infostroy Ltd.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.