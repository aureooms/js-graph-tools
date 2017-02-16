[js-graph-tools](http://aureooms.github.io/js-graph-tools)
==

graph tools code bricks for JavaScript

[![NPM license](http://img.shields.io/npm/l/@aureooms/js-graph-tools.svg?style=flat)](https://raw.githubusercontent.com/aureooms/js-graph-tools/master/LICENSE)
[![NPM version](http://img.shields.io/npm/v/@aureooms/js-graph-tools.svg?style=flat)](https://www.npmjs.org/package/@aureooms/js-graph-tools)
[![Bower version](http://img.shields.io/bower/v/@aureooms/js-graph-tools.svg?style=flat)](http://bower.io/search/?q=@aureooms/js-graph-tools)
[![Build Status](http://img.shields.io/travis/aureooms/js-graph-tools.svg?style=flat)](https://travis-ci.org/aureooms/js-graph-tools)
[![Coverage Status](http://img.shields.io/coveralls/aureooms/js-graph-tools.svg?style=flat)](https://coveralls.io/r/aureooms/js-graph-tools)
[![Dependencies Status](http://img.shields.io/david/aureooms/js-graph-tools.svg?style=flat)](https://david-dm.org/aureooms/js-graph-tools#info=dependencies)
[![devDependencies Status](http://img.shields.io/david/dev/aureooms/js-graph-tools.svg?style=flat)](https://david-dm.org/aureooms/js-graph-tools#info=devDependencies)
[![Code Climate](http://img.shields.io/codeclimate/github/aureooms/js-graph-tools.svg?style=flat)](https://codeclimate.com/github/aureooms/js-graph-tools)
[![NPM downloads per month](http://img.shields.io/npm/dm/@aureooms/js-graph-tools.svg?style=flat)](https://www.npmjs.org/package/@aureooms/js-graph-tools)
[![GitHub issues](http://img.shields.io/github/issues/aureooms/js-graph-tools.svg?style=flat)](https://github.com/aureooms/js-graph-tools/issues)
[![Inline docs](http://inch-ci.org/github/aureooms/js-graph-tools.svg?branch=master&style=shields)](http://inch-ci.org/github/aureooms/js-graph-tools)

Can be managed through [jspm](https://github.com/jspm/jspm-cli),
[duo](https://github.com/duojs/duo),
[component](https://github.com/componentjs/component),
[bower](https://github.com/bower/bower),
[ender](https://github.com/ender-js/Ender),
[jam](https://github.com/caolan/jam),
[spm](https://github.com/spmjs/spm),
and [npm](https://github.com/npm/npm).

## Install

### jspm
```terminal
jspm install github:aureooms/js-graph-tools
# or
jspm install npm:@aureooms/js-graph-tools
```
### duo
No install step needed for duo!

### component
```terminal
component install aureooms/js-graph-tools
```

### bower
```terminal
bower install @aureooms/js-graph-tools
```

### ender
```terminal
ender add @aureooms/js-graph-tools
```

### jam
```terminal
jam install @aureooms/js-graph-tools
```

### spm
```terminal
spm install @aureooms/js-graph-tools --save
```

### npm
```terminal
npm install @aureooms/js-graph-tools --save
```

## Require
### jspm
```js
let graphtools = require( "github:aureooms/js-graph-tools" ) ;
// or
import graphtools from '@aureooms/js-graph-tools' ;
```
### duo
```js
let graphtools = require( "aureooms/js-graph-tools" ) ;
```

### component, ender, spm, npm
```js
let graphtools = require( "@aureooms/js-graph-tools" ) ;
```

### bower
The script tag exposes the global variable `graphtools`.
```html
<script src="bower_components/@aureooms/js-graph-tools/js/dist/graph-tools.min.js"></script>
```
Alternatively, you can use any tool mentioned [here](http://bower.io/docs/tools/).

### jam
```js
require( [ "@aureooms/js-graph-tools" ] , function ( graphtools ) { ... } ) ;
```