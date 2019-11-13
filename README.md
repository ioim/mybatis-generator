#  MyBatis逆向工程

## 目录介绍

### src

生成的文件放在`src`目录下

### config.xml

配置文件

### *.jar

运行所需要的`jar`包

### 运行命令

在 cmd 中运行的命令

## config.xml中需要修改的地方

- 数据库驱动包位置：`location`修改为`mysql-connector-java-5.1.39.jar`所在的位置
- 数据库链接URL、用户名、密码：修改`connectionURL`、`userId`、`password`
- 生成entity包名和位置：修改`targetPackage`和`targetProject`
- 生成Mapper映射XML文件位置：修改`targetPackage`和`targetProject`
- 生成Mapper接口文件位置：修改`targetPackage`和`targetProject`
- 修改表名：`tableName="TEST_STUDENT" domainObjectName="TestStudent"`