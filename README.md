# html-table-column-hider

> Lightweight <1kb(minified) library to hide/unhide html table columns


## Install

```
$ npm install --save html-table-column-hider
```


## Usage

```js
var HtmlTableColumnHider = require('html-table-column-hider');

var uniqueTableSelector = '#elements-table-1';
var hider = new TableColumnHider(uniqueTableSelector);
hider.hideColumns([0,1,2]);
hider.unhideColumns([1]);

```


## API

### .hideColumns(*array*)

Takes array of integers representing one-based column indexes


### .unhideColumns(*array*)

Takes array of integers representing one-based column indexes


### .unhideAllColumns()


### .getHiddenColumns()

Returns array of integers representing one-based column indexes


### .destroy()

Removes attached style element from document head

## License

MIT © Tomas Kikutis