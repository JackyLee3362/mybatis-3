---
type: basic-note
title: wiki
author: JackyLee
create_time: 2025-11-05
update_time:
tags:
description:
---

## java.lang.AutoCloseable

java7 引入

主要是可以自动关闭资源，配合 try-with-resources 语句使用

## java.sql.Wrapper

用途是包装（wrap）和获取底层实现对象，适用于数据库的驱动抽象设计。

作用说明

```java
// 用于获取底层对象。如果你需要底层驱动的特定实现，可以调用 unwrap 得到原始对象。
unwrap(Class<T> iface)

// 判断当前对象是否包装了指定类型的实现。
isWrapperFor(Class<?> iface)
```

## java.sql.ResultSet

用于表示数据库查询结果集，以及遍历和读取数据行。

当使用 JDBC 的 SELECT 查询时，返回的就是一个 ResultSet 对象

使用 next() 可以迭代结果集

## java.sql.PreparedStatement

用于执行带参数的预编译 SQL 语句，通常用于防止 SQL 注入，提高性能，并简化参数化查询。

## java.sql.CallableStatement

在 Java 程序中调用数据库的存储过程（Stored Procedure）或存储函数（Stored Function）。

## 参考资料
