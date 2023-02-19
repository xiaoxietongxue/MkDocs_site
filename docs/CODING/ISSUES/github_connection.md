# 解决github登陆问题
## 问题描述
在借助git工具进行pull 和 push 操作时，经常出现连接不到服务器的情况


## 解决方案

https://www.ipaddress.com/ 在该网站上查询github.com的ip地址，把它添加到hosts文件夹下

一般情况下，在windows系统中，hosts文件位于
```
C:\Windows\System32\drivers\etc
```

在文件末尾添加一行
``` 
 20.205.243.166 github.com
```

注意，此处的ip是通过刚才的网址查询得到的

## 参考资料

> https://blog.csdn.net/weixin_44442186/article/details/124979085