```javascript
let arr = ["😎","🔥","🚀"]
const randomItem = arr => arr[(Math.random() * arr.length) | 0];

randomItem(arr)
"😎"
```

