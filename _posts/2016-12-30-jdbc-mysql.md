---
layout: post
title:  "JDBC(Mysql)"
date:   2016/12/30 15:55:51 
categories: [config]

---


 JAVA连接MySQL数据库，在操作值为0的timestamp类型时不能正确的处理，而是默认抛出一个异常，
就是所见的：

<p style="color:red">java.sql.SQLException: Cannot convert value '0000-00-00 00:00:00' from column 7 to TIMESTAMP。</p>