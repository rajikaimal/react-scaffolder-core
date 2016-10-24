# react-scaffolder-core

Core set of APIs used in react-scaffolder

> under development (unstable)

## Install

```
npm install --save react-scaffolder-core
```

## Usage

```js
const generateApp = require('react-scaffolder-core');
generate = new generateApp();

const answers = {
	"componentType": "child",
	"propTypes": "yes",
	"propNo": "2",
	"propName": "first",
	"propType": "number"
};

const answersInner = { 
	first: 'string', 
	last: 'string' 
};

generate.createComponent('core', 'sample', answers, answersInner, function(response) {
	console.log(response)
});
```

## License

MIT © [Rajika Imal](https://rajikaimal.github.io)