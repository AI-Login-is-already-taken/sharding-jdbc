+++
date = "2016-02-05T17:03:18+08:00"
title = "Release Notes"
weight = 1
+++

# Release Notes

## 1.1.0

### 新功能:

1. 增加Spring命名空间和YAML文件配置功能

### 缺陷修正:

1. [ISSUE #25](https://github.com/dangdangdotcom/sharding-jdbc/issues/25) OR表达式下会出现重复结果问题

## 1.0.1

### 功能提升:

1. 增加使用暗示(Hint)方式注册分片键值的方式进行SQL路由的功能

### 缺陷修正:

1. [ISSUE #11](https://github.com/dangdangdotcom/sharding-jdbc/issues/11) count函数在某些情况下返回不正确
1. [ISSUE #13](https://github.com/dangdangdotcom/sharding-jdbc/issues/13) Insert 语句 没有写列名 进行了全路由
1. [ISSUE #16](https://github.com/dangdangdotcom/sharding-jdbc/issues/16) 改造多线程执行模型
1. [ISSUE #18](https://github.com/dangdangdotcom/sharding-jdbc/issues/18) 查询Count时，使用getObject()取数会报异常
1. [ISSUE #19](https://github.com/dangdangdotcom/sharding-jdbc/issues/19) sum和avg函数，不加别名不执行merger，加了空指针异常
1. [ISSUE #38](https://github.com/dangdangdotcom/sharding-jdbc/issues/38) JPA与Sharding-JDBC的兼容问题。JPA会自动增加SELECT的列别名，导致ORDER BY只能通过别名，而非列名称获取ResultSet的数据。

## 1.0.0
1. 初始版本。