---
layout: post
title: "Tomcat8 Context"
description: ""
category:
tags: [Data]
---
{% include JB/setup %}

### Context in Tomcat

设Context一般用以下两种方法:

1. 在Web应用的文件夹下创建META-INF/context.xml, 但是docbase 只能用相对路径
2. 在&lt;CATALINA_HOME&gt;/conf/[enginename]/[hostname]/[contextpath].xml. docbase可用绝对路径.

1只能相对的理由我推测应该是既然都能在Web应用的目录下创建context.xml了为啥不把整个docbase放到Web应用的文件夹下. 2的话既然是在更高层的地方自然可以用绝对路径.


