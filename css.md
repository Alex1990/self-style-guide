# CSS 代码风格指南

## 缩进

2 个空格，禁止 Tab。

## 行尾空白符

禁止。

## 换行

- 一行只能写一个复合选择器；
- 一行只能写一条属性；
- 左花括号`{`必须在行尾；

```css
.arrow,
.arrow::after {
  font-size: 0;
  border: 1px solid transparent;
}
```

## 更多细节控制

可以使用 [csscomb](https://github.com/csscomb/csscomb.js) 来控制。

## 预处理器

LESS/SCSS/Stylus 也基本遵循该指南。

