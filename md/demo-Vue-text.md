# vue项目面试题

## ES6相关面试题

**var let const**

```
1.声明提升
console.log(num); // un
var num  = 123;

2.变量覆盖
var num1 = 10;
var num1 = 11;
console.log(num1); //11
如果换成let会报错，显示num1已经被定义

3.没有块级作用域
function(){
    for(var i =0;i<3;i++){
        console.log(i);
    }
    console.log(i);
}
如果换成let会报错，显示un

4.const声明之后必须赋值，否则会报错，而且不可以修改，支持let的其他属性
const demo =123;
demo=500;
console.log(demo);

```
> 如何使用es6的知识使ab的值互换 (解构赋值)
```
let a =1;
let b =2;

[a,b]=[b,a];
console.log(a,b)

```

## v-if和v-show的区别

> 区别最大的地方在于 对于不显示的元素的处理办法。v-if直接不渲染，v-show使用css的行内样式来让他display：block或是none

> 频繁的切换就用v-show，因为直接控制的display的属性。不频繁就用v-if，因为这个处理的方式是不渲染，频繁切换如果使用v-if那就等于是一直在创建和销毁这个元素。

## v-for渲染

> v-for的执行顺序比v-if高

## 父子组件通信 （props接收，$emit发送）

