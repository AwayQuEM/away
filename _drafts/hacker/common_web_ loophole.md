# 常见漏洞

> 漏洞就是 异常的`输入输出`处理

# SQL注入

> 所谓SQL注入，就是通过把SQL命令插入到Web表单提交或输入域名或页面请求的查询字符串，最终达到欺骗服务器执行恶意的SQL命令。


# XSS

> 跨站脚本攻击

> XSS则是攻击者往Web页面里插入恶意Script代码，当用户浏览该页之时，嵌入Web里面的Script代码会被执行，从而达到恶意攻击用户的目的。
[知乎回答](https://www.zhihu.com/question/21606800/answer/22268855)


# 远程命令执行

> 而远程命令执行，是用户通过浏览器提交执行命令，由于服务器端没有针对执行函数做过滤，导致执行命令。

# 越权

> 越权漏洞是比较常见的漏洞类型，越权漏洞可以理解为，一个正常的用户A通常只能够对自己的一些信息进行增删改查，但是由于程序员的一时疏忽 ，对信息进行增删改查的时候没有进行一个判断，判断所需要操作的信息是否属于对应的用户，可以导致用户A可以操作其他人的信息。

