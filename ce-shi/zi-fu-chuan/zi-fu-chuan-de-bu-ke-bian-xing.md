语法：

```
[public] enum 枚举名
{
         值1,
         值2,
         值3,
         ........
}
```

public:访问修饰符。公开的公共的，哪都可以访问。

enum：关键字，声明枚举的关键字

枚举名：要符合Pascal命名规范

将枚举声明到命名空间的下面，类的外面，表示这个命名空间下，所有的类都可以使用这个枚举。

枚举就是一个变量类型 ，int--double  string  decimal.

只是枚举声明、赋值、使用的方式跟那些普通的变量类型不一样。

我们可以将一个枚举类型的变量跟int类型和string类型互相转换。

枚举类型默认是跟int类型相互兼容的，所以可以通过强制类型转换的语法互相转换。

当转换一个枚举中没有的值的时候，不会抛异常，而是直接将数字显示出来。

枚举同样也可以跟string类型互相转换，如果将枚举类型转换成string类型，则直接调用ToString\(\).

如果将字符串转换成枚举类型则需要下面这样一行代码：

```
     \(要转换的枚举类型\)Enum.Parse\(typeof\(要转换的枚举类型\),"要转换的字符串"\);
```

如果转换的字符串是数字，则就算枚举中没有，也会不会抛异常。

如果转换的字符串是文本，如果枚举中没有，则会抛出异常。
