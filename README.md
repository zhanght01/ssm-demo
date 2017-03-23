# ssm-demo <br /> 

Spring+SpringMVC+mybatis+easy-ui实现的一个简单demo，项目为两年前做的一个项目，后续会逐渐优化改造。 <br /> <br /> 
ssm-demo仓库下会有三个项目，分别是ssm-demo、ssm-login、ssm-maven，ssm-demo为普通的JavaWeb工程，并没有引入maven管理项目， 
而ssm-maven则为maven改造后的项目，使用maven统一管理项目jar包及项目构建，后续的优化都会在这个项目里做。 <br /> 
# 项目地址： <br /> 
  <a href='http://ssm-demo.hanshuai.xin'>ssm-demo</a> <br /> 
  登录名：admin <br /> 
  密码：123456 <br /> 
  <a href='http://ssm-login.hanshuai.xin'>ssm-login</a> <br /> 
  登录名：admin <br /> 
  密码：123456 <br /> 
 修改
  
# 项目框架包括：
Spring <br /> 
SpringMVC <br /> 
MyBatis <br /> 
后端界面则使用easyui进行搭建 <br /> 

# 功能介绍：
本项目实现了一个简单的书籍仓库管理系统，主要包含以下功能： <br /> 
管理员的注册功能，登录功能，删除功能。 <br /> 
书籍的搜索功能，出库功能。 <br /> 
书架的添加功能，修改功能，搜索功能。 <br /> 

# 更新日志
  2017-02-23 初始化，接下来是bug修复，下一步打算将项目改为maven工程项目。 <br /> 
  2017-02-24 新增ssm-login项目，最基础的ssm项目搭建。 <br /> 
  2017-03-02 新增ssm-maven项目，Spring+SpringMVC+MyBatis+Maven+easyUI整合。 <br /> 
  2017-03-07 中文搜索bug修复。<br /> 
  2017-03-14 网友提醒:书架管理-查看书籍,JS报错 Cannot read property 'title' of null，数据原因，有些数据没删干净。 解决方法：delete from ssm_storebook where isbn not in (select id from ssm_book)。<br/>
