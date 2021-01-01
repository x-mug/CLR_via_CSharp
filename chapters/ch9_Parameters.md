# 第 9 章 参数

本章内容：

* <a href="#9_1">可选参数和命名参数</a>
* <a href="#9_2">隐式类型的局部变量</a>
* <a href="#9_3">以传引用的方式向方法传递参数</a>
* <a href="#9_4">向方法传递可变数量的参数</a>
* <a href="#9_5">参数和返回类型的设计规范</a>
* <a href="#9_6">常量性</a>

本章重点在于向方法传递的各种方式，包括如何可选地指定参数，按名称指定参数，按名称指定参数，按引用传递参数，以及如何定义方法来接受可变数量的参数。

## <a name="9_1">9.1 可选参数和命名参数</a>

设计方法的参数时，可为部分或全部参数分配默认值。然后，调用这些方法的代码可以选择不提供部分实参，使用其默认值。此外，调用方法时刻通过指定参数名称来传递参数。以下代码演示了可选参数和命名参数的用法：

```C#
using System;

```