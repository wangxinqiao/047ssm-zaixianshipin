# 047ssm在线视频教育网站
047ssm在线视频教育网站


#### 介绍
````
基于SSM的在线视频教育网站系统设计与实现.系统分为管理员与普通用户两种角色。
1)登录模块
在进入系统首页后，首先看到的是登录界面，该界面会提供注册用户的功能，在登陆界面，输入用户名之后，首先要发送ajax请求验证用户名是否存在，第一时间内给用户提示。
2)客户端模块
本模块分为密钥管理，角色管理，权限管理，个人信息，课程信息等组成。
3)后台管理模块
本模块包括用户管理，作品信息管理等。 
用户管理：提供管理员查询用户，锁定解锁用户，修改用户信息，充值余额。 
课程信息管理：提供管理员增加删除修改功能。 
系统日志查看：查看所有系统的动作信息。 
访问ip管理：提供对访问IP的管理，可以进行拉黑IP等操作。
````
源码获取地址：[ **点此获取** ](http://www.shuyue.fun/?type=productinfo&id=148)

演示地址：[ **点此查看** ](http://www.csbishe.cn:15038/mooc/)

管理员账号/密码：admin/admin
用户账号/密码： yuanmamatou/123456

#### 环境需要
```
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 否；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目
6.数据库：MySql 5.7版本；
```

#### 技术栈
```
1. 后端：SSM(Spring SpringMVC MyBatis)
2. 前端: JSP
```

#### 使用说明
```
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 将项目中jdbc.properties配置文件中的数据库配置改为自己的配置
3. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;
若为maven项目，导入成功后请执行maven clean;maven install命令，配置tomcat，然后运行；
4. 运行项目，输入localhost:8080/xx 登录; xx为项目路径；后台访问地址：localhost:8080/xx/admin
5. 普通用户：1823544517 测试密码：123654
管理员账户：admin 管理员密码：admin
充值密码以及删除密码为：591284209
```
## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/104743_b005d9b8_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/105052_fc0614f5_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/105103_da7f511b_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/105113_bf83b2d4_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/105124_b19f35d6_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/105134_73363dbb_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/105147_18d64fab_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/105156_4a246094_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/105205_d74e210b_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/105215_a8098787_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/105225_8afc1027_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/105237_95170844_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/105247_6f53c0ff_863230.png "屏幕截图.png")

