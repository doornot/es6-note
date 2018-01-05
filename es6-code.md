#### 1、数组去重
```javascript
var arr = [1,2,2,3]
[...new Set(arr)]
// 或者
Array.from(new Set(arr))
```