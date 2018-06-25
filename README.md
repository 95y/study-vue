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

/*
    v-pre指令：
        在模板中跳过vue的编译，直接输出原始值。就是在标签中加入v-pre就不会输出vue中的data值了。
    v-cloak指令：
        在vue渲染完指定的整个DOM后才进行显示。它必须和CSS样式一起使用，
    v-once指令：
        在第一次DOM时进行渲染，渲染完成后视为静态内容，跳出以后的渲染过程。
*/

```


##### 保存学习demo