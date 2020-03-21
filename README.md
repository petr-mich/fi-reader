# Module "FIReader"

## Description 
Simple file-input reader module extended with Drag&Drop API on JavaScript ES5/ES6.

## Usage
### ES5:

```js
var dropFIReader = new window.DropFIReader({
	fileTypes: ['jpeg', 'jpg', 'png', 'gif', 'svg'],
	fileInput: document.querySelector('input[type="file"]'),
	dropbox: document.querySelector('input[type="file"]').labels[0],
	resultHandler: function(images) {
		// handle images:
		// ...
	}
})
```

### ES6:

```js
const dropFIReader = new DropFIReader({
	fileTypes: ['jpeg', 'jpg', 'png', 'gif', 'svg'],
	fileInput: document.querySelector('input[type="file"]'),
	dropbox: document.querySelector('input[type="file"]').labels[0],
	resultHandler(images) {
		// handle images:
		// ...
	}
})
```
