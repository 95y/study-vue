# 阅读文档
```js
// 排序
function sort (a, b) {
    return (a - b);
}

//数组对象方法排序: 
function sortByKey(array, key) {
    return array.sort(function (a, b) {
        var x = a[key];
        var y = b[key];
        return ((x <
            y) ? -1 : ((x > y) ? 1 : 0));
    });
}