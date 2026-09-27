# Mybatis

通过java操作数据库；

MyBatis是一款优秀的**持久层（dao数据访问层）** 框架，用于简化*JDBC* 的开发

---

## 一、入门

dataGrip操作数据库步骤：sql语句发给sql服务器并执行，然后服务器将结果返回给GUI，Mybatis替换GUI就是原理；底层原理想通

1、准备工作(创建springboot工程、数据库表user、实体类User)

2、引入Mybatis的相关依赖，配置Mybatis(数据库连接信息）

3、编写SQL语句(通过注解/XML定义sql语句)

数据库四要素：驱动类全类名、数据库连接URL、访问数据库的账密；
