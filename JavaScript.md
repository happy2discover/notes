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
#### 2. 转成字符串
```
var num = 10;
num.toString(2);    // 转换成二进制
num.toString(8);    // 转换成八进制
num.toString(16);   // 转换成十六进制
```
#### 3. 转换成数字
```
var num = parseInt("10", 2);    // 转换成二进制
var num = parseInt("10", 8);    // 转换成八进制
var num = parseInt("10", 10);   // 转换成十进制
var num = parseInt("10", 16);   // 转换成十六进制
```
#### 4. 强制类型转换
```
Boolean(50);
Number(50);
String(50);
```
#### 5. “==”和“===”
```
var a = 3;
var b = "3";  // a == b
var c = "3";  // b === c
```
#### 6. 无符号右移
```
var a = 1024;
a >>> 2
```
#### 7. for-in
```
for(var item in items) {
  console.log(item);
}
```
#### 8. break label;
```
search: for(var i = 0; i < items; i++) {
  for(var j = 0; j < books; j++) {
    break search;
  }
}
```
