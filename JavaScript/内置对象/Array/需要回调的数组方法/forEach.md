1. 功能：遍历数组
2. 语法：`str.forEach(callback)`

- `callback`：在数组每一项上执行的函数，接收 3 个参数：

* item：数组的每一项
* index：每一项的下标
* array：被遍历的数组

3. 用法：

```js
let arr = ['1', '2']
arr.forEach((item, index, array) => {
  console.log(item) //1,2
})
```
