#### 1. 省略了分号的语句怎么解析？
##### 1.1
```
x
++
y
```
结果是
```
x; ++y
```
而不是
```
x++; y
```
##### 1.2
```
var y = x + f
(a+b).toString()
```
结果是
```
var y = x + f(a+b).toString();
```
### 2. 转成字符串
```
var num = 10;
num.toString(2);    // 转换成二进制
num.toString(8);    // 转换成八进制
num.toString(16);   // 转换成十六进制
```
### 3. 转换成数字
```
var num = parseInt("10", 2);    // 转换成二进制
var num = parseInt("10", 8);    // 转换成八进制
var num = parseInt("10", 10);   // 转换成十进制
var num = parseInt("10", 16);   // 转换成十六进制
```
