# Js面试题

## 1、js的数据类型有哪些

> 简单数据类型: number string boolean undefined null 复杂数据类型: object  function  array

## 2、typeof返回的数据类型

> number string boolean undefined  object  function 
> >  特殊情况：
> >  typeof null -->object
> >  typeof array -->object
> >  typeof typeof 任何类型  -->string

## 3、返回false的情况有哪些

> 0  ""   null  false  NaN  undefined  不成立的表达式

## 4、==和===的区别

> == 表示是相等，只比较内容  === 表示是全等，不仅比较内容，也比较类型

## 5、null和undefined的区别

> null 表示空值 没有获取到。typeof null 返回"object"

> undefined 表示未定义，声明没有值。typeof undefined 返回"undefined"

## 6、js的运行机制是什么

> js是单线程执行的，页面加载时，会自上而下执行主线程上的同步任务，当主线程代码执行完毕时，才开始执行在任务队列中的异步任务。具体如下  

```
1.所有同步任务都在主线程上执行，形成一个执行栈。
2.主线程之外，还存在一个"任务队列(eventloop队列或者消息队列)"。只要异步任务有了运行结果，就在"任务队列"之中放置一个事件。
3.一旦"执行栈"中的所有同步任务执行完毕，系统就会读取"任务队列"，看看里面有哪些事件。哪些对应的异步任务，于是结束等待状态，进入执行栈，开始执行。
4.主线程不断重复上面的第三步。

```

## 7、怎么理解面向对象

```
1、面向对象是一种软件开发的思想和面向过程是相对应的，就是把程序看作一个对象，将属性和方法封装其中，以提高代码的灵活性、复用性、可扩展性。

2、面向对象有三大特性：封装、继承、多态。
    封装：把相关的信息（无论数据或方法）存储在对象中的能力
    继承：由另一个类（或多个类）得来类的属性和方法的能力
    多态：编写能以多种方法运行的函数或方法的能力

3、js中对象是一个无序的数据集合或者也可以说是属性和方法的集合，可以动态的添加属性可方法。

4、js是基于对象，但是也使用了嵌入了面向对象的思想，可以实现继承和封装，这样也可以提供代码的灵活性和复用性。

```

## 8、伪数组和真数组的区别

```
伪数组：
1、拥有length属性
2、不具有数组的方法
3、伪数组是一个Object，真数组是Array
4、伪数组的长度不可变，真数组的长度是可变的

```

## 9、那些情况会得到伪数组

```
1、参数 arguments，
2、DOM 对象列表（比如通过 document.getElementsByTags 得到的列表）、childNodes也是伪数组

```

## 10、let、const、var的区别

```
1、var声明变量存在提升（提升当前作用域最顶端），let和const是不存在变量提升的情况
2、var没有块级作用，let和const存在块级作用域
3、var允许重复声明，let和const在同一作用域不允许重复声明
4、var和let声明变量可以修改，const是常量不能改变

```

## 11、怎么理解事件循环机制

```
1、JavaScript 是一门单线程语言.单线程可能会出现阻塞的情况，所js分了同步任务和异步任务。
2、同步和异步任务分别进入不同的执行环境，同步的进入主线程，即主执行栈，异步的进入 Event Queue（事件队列） 。主线程内的任务执行完毕为空，会去 Event Queue 读取对应的任务，推入主线程执行。 上述过程的不断重复就是我们说的 Event Loop (事件循环)。

```

## 12、for in 和 for of 的区别

```
1、for…in是遍历数组、对象的key
2、for…of是遍历数组的value
**for of 遍历数组**
**for in 遍历对象**
for in遍历的是数组的索引（即键名），
而for of遍历的是数组元素值。
for in的一些缺陷:
索引是字符串型的数字，因而不能直接进行几何运算
遍历顺序可能不是实际的内部顺序
for in会遍历数组所有的可枚举属性，包括原型。例如的原型方法method和name属性
故而一般用for in遍历对象而不用来遍历数组
这也就是for of存在的意义了,for of 不遍历method和name,适合用来遍历数组
那for of有缺点吗? 当然有了:
for of不支持普通对象，想遍历对象的属性，可以用for in循环, 或内建的Object.keys()方法：
Object.keys(myObject)获取对象的实例属性组成的数组，不包括原型方法和属性

```