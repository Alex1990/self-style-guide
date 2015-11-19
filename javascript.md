# JavaScript 风格指南

个人 JavaScript 代码风格简要规范，大体上同 [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript) 一致，更多细节可参考它。

## 命名

- 小驼峰，即首字母小写，后面每个单词首字母大写，如`userName`；
- 不要使用过于简短的名字，比如只用一个字母，除非用于循环中的计数器，如`i`；
- 构造函数的函数名称首字母大写；
- 以上命名，通常不要使用汉语拼音，不要出现单词拼写错误；

## 变量声明

- 一行使用一个`var`

## 引号

- 字符串字面量使用单引号，如`var foo = 'Hello, world!';`；

## 缩进

- 使用空格替代 Tab，2 个空格；

## 分号

- 语句结尾必须加分号；

## 空格

为了提高代码可读性，需要在下面位置使用空格：

- 赋值操作符、二元或三元运算符的两侧，如`=`/`+`/`>`；
- 数组字面量，对象字面量及函数参数列表的逗号`,`后面；
- 对象属性名的冒号`:`后面；
- 表达式或函数参数列表两侧与小括号之间；
- `if`/`else`/`for`/`while`/`switch`/`try`/`function`等关键字的后面
- 左花括号`{`的前面

## 空行

- 语句块前后适当添加空行；

## 行尾空白符

- 行尾后面不能有空格或其他空白符；

## 花括号

- `if`/`else`语句只有一行时，花括号可省略；

## 条件表达式

- 使用全等运算符`===`或不全等运算符`!==`，但与`null`比较时可用`==`/`!=`；

## 其他参考风格

- [jQuery JavaScript Style Guide](http://contribute.jquery.org/style-guide/js/)
- idiomantic.js: [English](https://github.com/rwaldron/idiomatic.js) [中文](https://github.com/rwaldron/idiomatic.js/tree/master/translations/zh_CN)
- Airbnb: [English](https://github.com/airbnb/javascript) [中文](https://github.com/adamlu/javascript-style-guide)


## 内置对象

- 禁止扩展内置对象
