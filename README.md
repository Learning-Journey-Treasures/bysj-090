# 1.项目介绍
- 系统角色：管理员、员工、普通用户
- 功能模块：用户管理、员工管理、汽车类型管理、汽车信息管理、预约试驾管理、销售订单管理、配件类型管理、订单信息管理、部门信息管理等
- 技术选型：SSM，Vue（后端管理web），Layui（门户）等
- 测试环境：idea2024，jdk1.8，mysql5.7，maven3，tomcat8
# 2.项目部署
- 创建数据库，导入sql文件
- idea打开项目，根据本地数据库环境修改 src/main/resources/config.properties  3-5行 （如果你本地数据库是8.0的，注意替换pom里依赖的版本、以及第三行配置serverTimezone，这都是基础，百度遍地都是。）
- 配置tomcat，启动项目，其中，我将deployment下的application contex配置为 /ssmrn6a1  http://localhost:8080/ssmrn6a1/admin/dist/index.html   管理员账号密码：abo/abo， 其他自行查表
- 门户页面：http://localhost:8080/ssmrn6a1/front/index.html
- 说明：vue项目是src/main/webapp/admin，上面的链接是直接运行了编译后的文件，如果你要对页面做一些修改，可以通过vscode或者webstorm去打开vue项目进行修改
# 3.项目部分截图
![输入图片说明](1.png)
![输入图片说明](2.png)
![输入图片说明](3.png)
![输入图片说明](4.png)
![输入图片说明](5.png)
![输入图片说明](6.png)
![输入图片说明](7.png)
![输入图片说明](8.png)
![输入图片说明](9.png)
![输入图片说明](91.png)
![输入图片说明](92.png)
![输入图片说明](93.png)

# 4.获取方式
[戳我查看](https://gitee.com/aven999/mall)
