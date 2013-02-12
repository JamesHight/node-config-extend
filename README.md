node-extend
===========

Object extend function designed for config files.

Modified version of node module node.extend.


Installation
------------

	npm install config-extend

Usage
-----

````javascript
var configExtend = require('config-extend'),
	obj1 = {
		foo: 'bar',
		bar: 'foo'
	},
	obj2 = {
		bar: [
			'foo',
			'foo',
			'foo'
		]
	},
	obj3 = {
		foo: 'test'
	},
	objCombined = configExtend(obj1, obj2, obj3);
````