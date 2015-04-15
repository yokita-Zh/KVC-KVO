# KVC-KVO
KVC and KVO
### 什么是KVC --->What
---
KVC指的就是NSKeyValueCoding⾮非正式协议。 KVC是⼀一种间接地访问对象的属性的机制。
这种间接表现在通过字符串来标识属性,⽽而不是通过调⽤用存取⽅方法或直接地访问实例变量的⽅方
式。
KVC机制不仅⽀支持对象,还⽀支持标量和结构体类型,这些⾮非对象的类型会被⾃自动的装箱和开 箱。
### Key & Key Path
键(Key)是⼀一个字符串⽤用来标识对象⾥里⾯面的⼀一个指定的属性。⼀一般⼀一个键对应对象的存取⽅方法或 实例变量。键必须是ASCII码,⼀一般以⼩小写字⺟母开始,不能包含空格。
A key path is a string of dot separated keys that is used to specify a sequence of object properties to traverse. The property of the first key in the sequence is relative to the receiver, and each subsequent key is evaluated relative to the value of the previous property.
键路径(Key Path)是⼀一个由点进⾏行分割的⼀一系列键组成的字符串
