# FaultManagementSystem
## 0x01.MyBatis

1. mybatis逆向工程生成model、mapper、example、xml等时，第二次覆盖生成前需要将xml删除。否则，第二次生成的xml中会有重复。

## 0x02.工程导入

1. 工程导入时，如果idea一直报编译错误，需要检查一下几点：

   ①项目所用jdk是否符合pom.xml中；

   ②maven的配置，如：setting配置中有多余字段等。

   ​	maven出错时直接在目录中mvn install生成jar文件看哪里出错。