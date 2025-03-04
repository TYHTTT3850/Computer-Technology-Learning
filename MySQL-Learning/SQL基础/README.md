## SQL 基本知识

### SQL 通用语法

- SQL 语句可以单行或多行书写，以分号结尾。

- SQL 语句可以使用空格/缩进来增强语句的可读性。

- MySQL 数据库的 SQL 语句**不区分大小写**，关键字建议使用大写。

- 注释：

  - 单行注释：`-- 注释内容` 或 `# 注释内容` 。

  - 多行注释：`/* 注释内容 */` 。

对 SQL 语句的用法进行讲解时，约定 `[]` 包围的代表可选项。 

### SQL 分类

SQL 语句，根据其功能，主要分为四类：DDL、DML、DQL、DCL。

| 分 类 |            全称            |                          说明                          |
| :---: | :------------------------: | :----------------------------------------------------: |
|  DDL  |  Data Definition Language  |   数据定义语言，用来定义数据库对象(数据库，表，字段)   |
|  DML  | Data Manipulation Language |     数据操作语言，用来对数据库表中的数据进行增删改     |
|  DQL  |    Data Query Language     |         数据查询语言，用来查询数据库中表的记录         |
|  DCL  |   Data Control Language    | 数据控制语言，用来创建数据库用户、控制数据库的访问权限 |
