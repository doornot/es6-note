#### ruanyifeng-es6-summary

工作中写js尽量使用es6语法，熟悉巩固es6。

es6带来编程便捷的地方、容易混淆的语法。
变量的解构赋值，扩展运算符，rest参数。

#### 一、 let 取代 var

#### 二、 变量的结构赋值用途
1. 交换变量的值
2. 从函数返回多个值
3. 提取 JSON 数据
4. 遍历 Map 结构
5. 输入模块的指定方法

#### 三、 字符串的扩展
1. 模板字符串，用反引号（`）标识。
2. 新增了几个字符串操作的方法。
3. 实例：模板编译
4. 标签模板：概念及应用

#### 四、 数值的扩展
1. 二进制、八进制
2. 新增了几个Number的方法
3. Math 对象的扩展

#### 五、 函数的扩展
1. 参数默认值
2. rest参数
3. 箭头函数与this
4. 尾调用与尾递归
5. 递归函数的改写

#### 六、 数组的扩展
1. 扩展运算符，可看做 rest 参数的逆运算。
2. 扩展运算符应用：
* （1）替代函数的 apply 方法；
* （2）复制数组；
* （3）合并数组；
* （4）与解构赋值结合用于生成数组；
* （5）将字符串转为真正的数组；
* （6）任何 Iterator 接口的对象都可以用扩展运算符转为真正的数组。
3. Array.from() 用途
* （1）将类似数组的对象（array-like object）转为真正的数组；
* （2）将可遍历（iterable）的对象（包括 ES6 新增的数据结构 Set 和 Map）转为真正的数组；
* （3）可以将各种值转为真正的数组，并且还提供map功能。
4. 三个新的方法：entries()，keys()和values()，用于遍历数组。

#### 七、 对象的扩展
1. 属性和方法的简洁表示法 
2. Object.is()：同值相等
3. Object.assign()常见用途
* （1）为对象添加属性
* （2）为对象添加方法
* （3）克隆对象
* （4）合并多个对象
* （5）为属性指定默认值
4. 属性的遍历
* （1）for...in
* （2）Object.keys(obj)
* （3）Object.getOwnPropertyNames(obj)
* （4）Object.getOwnPropertySymbols(obj)
* （5）Reflect.ownKeys(obj)
5. __proto__属性，Object.setPrototypeOf()，Object.getPrototypeOf()
6. super 关键字
7. Object.keys()，Object.values()，Object.entries()
8. 对象的扩展运算符

#### 八、 Symbol
1. 作为属性名的 Symbol
2. 实例：模块的 Singleton 模式

#### 九、 Set 和 Map 数据结构
1. ES6 提供了新的数据结构 Set。它类似于数组，但是成员的值都是唯一的。
2. Set 实例的属性（2个）和方法（操作方法 - 用于操作数据；遍历方法 - 用于遍历成员）。
3. ES6 提供了 Map 数据结构。它类似于对象，也是键值对的集合，但是“键”的范围不限于字符串，各种类型的值（包括对象）都可以当作键。
4. Map 实例的属性和操作方法。

#### 十、 Proxy
1. Proxy 属于一种“元编程”，即对编程语言进行编程。

#### 十一、 Reflect
1. Reflect对象与Proxy对象一样，也是 ES6 为了操作对象而提供的新 API。
2. 实例：使用 Proxy 实现观察者模式

#### 十二、 Promise 对象
1. Promise.prototype.then()
2. Promise.prototype.catch()
3. Promise.all()
4. Promise.race()
5. Promise.resolve()
6. Promise.reject()

#### 十三、 Iterator 作用
##### 背景
JavaScript 原有的表示“集合”的数据结构，主要是数组（Array）和对象（Object），ES6 又添加了Map和Set。这样就有了四种数据集合，用户还可以组合使用它们，定义自己的数据结构，比如数组的成员是Map，Map的成员是对象。这样就需要一种统一的接口机制，来处理所有不同的数据结构。
1. 一是为各种数据结构，提供一个统一的、简便的访问接口；
2. 二是使得数据结构的成员能够按某种次序排列；
3. ES6 创造了一种新的遍历命令for...of循环，Iterator 接口主要供for...of消费。

#### 十四、 Generator
1. Generator 函数是 ES6 提供的一种异步编程解决方案，语法行为与传统函数完全不同。

#### 十五、 async 函数
1. ES2017 标准引入了 async 函数，使得异步操作变得更加方便。它是 Generator 函数的语法糖。
2. async、await

#### 十六、 Class 的基本语法
1. ES6 的class可以看作只是一个语法糖，它的绝大部分功能，ES5 都可以做到，新的class写法只是让对象原型的写法更加清晰、更像面向对象编程的语法而已。
2. Class 可以通过extends关键字实现继承，这比 ES5 的通过修改原型链实现继承，要清晰和方便很多。
3. super 关键字

#### 十七、 Decorator
1. 类的修饰
2. 方法的修饰

#### 十八、 Module 的语法
1. export 命令
2. import 命令
3. export default 命令
4. 浏览器加载
5. ES6 模块与 CommonJS 模块的差异
6. Node 加载
