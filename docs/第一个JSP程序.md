## 第一个JSP程序

语言学习入门的第一个程序一般都是输出 "Hello World"，JSP输出 "Hello World" 代码如下所示：

```JSP
<html>
    <head>
           <title>第一个 JSP 程序</title>
    </head>
    <body>
           <%
                  out.println("Hello World！");
           %>
    </body>
</html>
```



## java代码格式

局部代码块：<% java代码块 %>

全局代码块：<%! Java代码块 %>

脚本代码块：<%=变量/方法 %>



## 注释

html注释 <!-- -->

css注释 /* */

js注释 //

java注释 //

jsp注释<%- -%>



## 静态包含与动态包含

静态引入<%@include file=”被引入的路径” %>

动态引入<jsp:include page=”被引入文件的相对路径”></jsp:include>