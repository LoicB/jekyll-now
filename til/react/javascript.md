How to to get from an array the item with a give ID (here 4)

```javascript
var index = myArray.map(function(el) {
  return el.id;
}).indexOf(4);
```

[Source](https://stackoverflow.com/questions/12553274/getting-index-of-an-arrays-element-based-on-its-properties)