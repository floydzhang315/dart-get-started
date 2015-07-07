# 关于 main() 函数及其他顶级函数

Dart 允许你定义顶级函数，这些函数不会封装在一个类或者对象当中，所有的应用程序都至少有一个顶级函数，即 `main()` 函数。

你可以看到在本教程中的 2 个应用中有其他的顶级函数。在 `HelloWorld` 案例中调用了 `print()` 函数，一个声明在 `dart:core` 中的顶级函数。而 `simple` 程序调用了 `querySelector().text` ，一个声明在 `dart:html` 中的顶级函数。

一个函数的声明包含两个部分：署名（Signature）和主体

![](images/function_parts.png)

署名设置了函数的名称，返回值的数据类型，以及输入参数数量及类型。

![](images/signature_parts.png)

主体代码则声明了函数相关行为的代码，他通常都会出现在花括号里面( `{code}` )。如果你的主体是一个简单表达式，你可以跳过括号使用 `=>` 作为简写:

`double milesToKM(double miles) => miles/0.62;`

这个函数接收了一个参数。函数可以有多个参数,在这种情况下,参数之间用逗号分开。