# Get maximum value of `z-index` in Document

[![npm version](https://badge.fury.io/js/%40saekitominaga%2Fdocument-zindex.svg)](https://badge.fury.io/js/%40saekitominaga%2Fdocument-zindex)

Get maximum value of `z-index` in Document.

## Demo

- [Demo page](https://saekitominaga.github.io/document-zindex/demo.html)

## Examples

```
import DocumentId from '@saekitominaga/document-zindex';

const documentZindex = new DocumentId();
documentZindex.getMaximum();
documentZindex.getMaximum('#foo > .bar');
```

## Methods

| Name | Returns | Description |
|-|-|-|
| getMaximum(selectors = 'body *') | {number} Maximum value of `z-index` inside the target element | Get maximum value of `z-index` inside the target element |
