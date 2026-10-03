# Day-03

## 公共字段自动填充

四个字段；

统一处理就需要AOP切面统一处理；

为Mapper方法加入注解：

1、自定义注解AutoFill，

2、自定义切面类AutoFillAspect，通过反射赋值？

3、加AutoFill注解

Enum标注操作类型

execution: `@annotation(com.sky.annotation.AutoFill)` 筛选有AutoFill的注解；

## 新增菜品

分类管理；

引用：防止泄露
