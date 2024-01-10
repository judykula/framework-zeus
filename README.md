
# 概要

整套架构的项目名称以DOTA2中的英雄名称命名

## zeus

parent项目，负责定义框架/插件版本

### 1.0.0

继承"spring-boot-starter-parent"实现jar包版本控制

如下统一信息子项目无须再设置：

- 统一utf8 
- 统一jdk:8 
- 统一基础spring cloud 版本 维持spring boot 2.7 对应的最新版
- 统一java工具：guava & apache common