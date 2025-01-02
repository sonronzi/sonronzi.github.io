---
title: SQL 必知必会 Learning Notes
author: sonronzi
date: 2025-01-02 14:50:48
home_cover:
home_cover_height:
post_cover:
post_cover_height:
categories:
- SQL
tags:
- SQL
---

极客时间专栏课程[《SQL 必知必会》（陈旸）](https://time.geekbang.org/column/intro/100029501?tab=catalog)学习笔记！
<!-- more -->
<br/>

# 开篇词 (1讲)

## 开篇词丨SQL可能是你掌握的最有用的技能

- **数据库操作中有大量的时间都花在了`I/O`上， `I/O`是 DBMS 最容易出现瓶颈的地方**
- 编写SQL时要注重效率，需要考虑的点：
  - 减少 I/O 操作（可以通过执行计划了解）
  - 降低 CPU 的计算量（在 SQL 语句中使用 GROUP BY、ORDER BY 等这些语句会消耗大量的 CPU 计算资源）
  - 内存使用情况
- 了解最新的数据库管理技术：
  - 基础：SQL语法，这些语法在不同的RDBMS中是如何使用的
  - 进阶：实际工作中使用 SQL 经常会遇到的问题；如何使用工具进行分析，快速定位性能问题及解决方案
  - 高级：各种主流数据库管理系统的使用
  - 实战：梳理SQL的知识体系；结合数据分析的项目讲解 SQL 的实战案例（比如如何用 SQL 做数据清洗、数据集成等）

<br/>

<br/>

<br/>

# 第一章：SQL语法基础篇 (19讲)

## 01丨了解SQL：一门半衰期很长的语言

### SQL是一门半衰期很长的语言

- 1974 年，IBM 研究员发布了一篇揭开数据库技术的论文《SEQUEL：一门结构化的英语查询语言》
- SQL 有两个重要的标准
  - SQL92（92年颁布的SQL标准）
  - SQL99（99年颁布的SQL标准）

<br/>

### SQL概述

- SQL是一门声明性语言（我们不需要指定具体的执行步骤，比如先执行哪一步，再执行哪一步，在执行前是否要检查是否满足条件 A 等等这些传统的编程思维）

- SQL 语言按照功能划分成以下的 4 个部分：
  - DDL（Data Definition Language|数据定义语言），用来定义我们的数据库对象，包括数据库、数据表和列。通过使用 DDL，我们可以创建，删除和修改数据库和表结构。
  - DML（Data Manipulation Language|数据操作语言），用它操作和数据库相关的记录，比如增加、删除、修改数据表中的记录
  - DCL（Data Control Language|数据控制语言），用它来定义访问权限和安全级别
  - DQL（Data Query Language|数据查询语言），用它查询想要的记录，它是 SQL 语言的重中之重
- SQL 语言定义了我们的需求，而不同的 DBMS（数据库管理系统）则会按照指定的 SQL 帮我们提取想要的结果

<br/>

### ER图（Entity Relationship Diagram）

- SQL 是我们与 DBMS 交流的语言，我们在创建 DBMS 之前，还需要对它进行设计，对于 RDBMS 来说采用的是 ER 图（Entity Relationship Diagram），即实体 - 关系图的方式进行设计。
- ER 图评审通过后，我们再用 SQL 语句或者可视化管理工具（如 Navicat）创建数据表
- 实体 - 关系图是我们用来描述现实世界的概念模型，在这个模型中有 3 个要素：实体、属性、关系
  - 实体：就是我们要管理的对象
  - 属性：是标识每个实体的属性
  - 关系：是指对象之间的关系（例如一对一，一对多，多对多）

<br/>

### SQL书写规范

- 表名、表别名、字段名、字段别名等都小写
- SQL 保留字、函数名、绑定变量等都大写
- [MySQL 开发规范](https://zerolee1993.github.io/mysql-guide/)

<br/>

### 总结

- 学习路径：先掌握基本的 DDL、DML、DCL 和 DQL 语法，再了解不同的 DBMS 中的 SQL 语法差异，然后再来看如何优化，提升 SQL 的效率
- 要想写出高性能的 SQL，首先要了解它的原理，其次就是做大量的练习

<br/>

<br/>

## 02丨DBMS的前世今生













<br/>

<br/>

<br/>

# Reference

- [MySQL 开发规范](https://zerolee1993.github.io/mysql-guide/)
- SQL学习、练习网站：
  - [SQLZOO](https://sqlzoo.net/)
  - [XUESQL](http://xuesql.cn/)
  - [牛客网](https://www.nowcoder.com/exam/oj?tab=SQL%E7%AF%87&topicId=82)
  - [leetcode](https://leetcode.cn/problemset/database/)







<br/>

<br/>

<br/>

# remarkv

> 1. 





