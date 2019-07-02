# @tohmn/menu

[![npm version](https://img.shields.io/npm/v/@tohmn/menu.svg)](https://github.com/tohmn/menu)

## Installation

```sh
$ npm install @tohmn/menu
```

## Usage

### Data Attribute Settings

Example:

```html
<a href="#menu-content" data-menu-toggle>MENU</a>
<div id="menu-content" data-menu-content data-menu='{"enterFrom": right, "height": 100vw, "width": 80vh'>
  Contents of the menu.
</div>
```

### JavaScript Settings

Example:

```javascript
import '@tohmn/menu';

menuGenerator({
  enterFrom: 'right',
});
```


### Settings

| Option | Type | Default | Description |
| --- | --- | --- | --- |
| enterFrom | string | top | Specify from where the menu-content should enter the screen |

## License and Copyright

This software is released under the terms of the [MIT license](https://github.com/tohmn/menu/blob/master/LICENSE).
