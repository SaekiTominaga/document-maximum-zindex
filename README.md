# Get maximum value of `z-index` in Document

[![npm version](https://badge.fury.io/js/%40saekitominaga%2Fdocument-maximum-zindex.svg)](https://badge.fury.io/js/%40saekitominaga%2Fdocument-maximum-zindex)

Get maximum value of `z-index` in Document.

## Demo

- [Demo page](https://saekitominaga.github.io/document-maximum-zindex/demo.html)

## Examples

```JavaScript
import DocumentMaximumZindex from '@saekitominaga/document-maximum-zindex';

const documentMaximumZindex = new DocumentMaximumZindex();
documentMaximumZindex.getMaximum();
documentMaximumZindex.getMaximum('#foo > .bar');
```

## Methods

<dl>
<dt><code>getMaximum(selectors = 'body *'): number</code></dt>
<dd>Get maximum value of <code>z-index</code> inside the target element</dd>
</dl>
