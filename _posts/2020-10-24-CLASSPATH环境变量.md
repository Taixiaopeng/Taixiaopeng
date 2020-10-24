---
layout: post
title:  "CLASSPATH环境变量"
date:   2020-10-24 22:14:54
categories: java 
tags: java 编程 JDK

---

* content
{:toc}




### CLASSPATH

1. 含义：JVM程序解释的时候从classpah加载类路径。

2. 需求：在任何路径下均可执行程序解释。

3. JVM解释字节码文件时需要classpath

4. 默认所有解释的类都在当前目录下  .

5. CLASSPATH还是应该保持默认设置。

6. 某些java程序安装可能会改变CLASSPATH的设置

7. PATH：

   + CLASSPATH：由JRE解释java程序时加载的类路径。

   + 关系：JVM——CLASSPATH加载类---解释字节码文件。

   