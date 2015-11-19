# Shell 代码风格简要指南

## 命名

- **函数**：全小写字母，下划线分隔。
- **变量**：同函数命名一样。
- **常量和环境变量**：全大写字母，下划线分隔，声明在文件顶部。
- **源文件名**：全小写字母，下划线分隔。

## 缩进

两个空格，禁止 Tab。

## 行尾空白符

禁止行尾空白符。

## 行宽

尽可能 80 列内，使用反斜杠（backslash）`\`断行。

## 函数定义

## if 语句

`then`与`if`同行：

```shell
if condition 1; then
  ...
elif condition 2; then
  ...
else
  ...
fi
```

## 循环

`do`和`for`或`while`同行：

```shell
for name in foo bar baz; do
  ...
done

while true; do
  ...
done
```

## Case

条件测试与结束符`;;`单独一行：

```shell
case "$OS" in
  Linux)
    echo "This is a Linux system"
    ;;
  Darwin)
    echo "This is a Mac system"
    ;;
  *)
    echo "Unknown OS $OS" >$2
    ;;
esac
```

## 条件测试

`[[ ... ]]``要比`[ ... ]`或`test`更好。

## exit vs return

函数内部只使用`return`，`exit`只用于主程序。

## 内置命令与外部命令

尽可能使用内置命令。

## 参考

- [Google Shell Style Guide](https://google.github.io/styleguide/shell.xml#Indentation)
- [yamttw Shell Style Guide](https://github.com/ymattw/shell-style-guide/blob/master/shell-style-guide-cn.md)
