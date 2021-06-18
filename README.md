# Web-APIs-Records
There're web apis that I interested in, I recorded them with mdn refs.

## `<template>`

The <template> HTML element is a mechanism for holding HTML that is not to be rendered immediately when a page is loaded but may be instantiated subsequently during runtime using JavaScript. [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/template)
  
## `importNode` `adoptNode` `cloneNode`
  
[importNode](https://developer.mozilla.org/en-US/docs/Web/API/Document/importNode) clone a node
  
[adoptNode](https://developer.mozilla.org/en-US/docs/Web/API/Document/adoptNode) remove node from a place to another
  
[cloneNode](https://developer.mozilla.org/en-US/docs/Web/API/Node/cloneNode) clone a node, the caller is different with importNode.
  
`document.importNode(node, deep)`
  
`node.cloneNode(deep)`
  
## Selection API

[MDN](https://developer.mozilla.org/en-US/docs/Web/API/Selection)
  
[This article](https://css-tricks.com/how-to-create-actions-for-selected-text-with-the-selection-api/) introduced a demo to use this API.
  
![text-selection-menu](https://user-images.githubusercontent.com/20169617/122502325-ff929d80-d028-11eb-8c25-83caa2cec751.gif)
