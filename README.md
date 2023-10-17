**完整代码 +  QQ: 316595344     或   WX: lz316595344  咨询**

**接毕业设计和论文**

**如果图片加载不出来可以去博客看 https://blog.csdn.net/qq_56450993/article/details/133892270**

**毕业设计所有选题地址**

**[github]👉https://github.com/XinChennn/allProjects**

**[忻辰的个人博客]👉https://www.ixinjiu.cn/articles/156**

# 基于Spring Boot的食堂管理系统

## 项目介绍
本项目是基于Java的管理系统。采用前后端分离开发。前端基于bootstrap框架实现，后端使用Java语言开发，技术栈包括但不限于SpringBoot、MyBatis、MySQL、Maven等，开发工具为IDEA。

## 功能介绍
- 主页
	- 简介（文本）
	- 店家热度（店家所有菜品销量总和排名）
	- 店家评分展示（评分：平均分、展示方式：树状图）
	- 菜品热度（菜单品的销量排名）
- 登录/注册（单独页面）
	- 区分登陆的用户可以干啥（如店家可以干啥、学生可以干啥、管理员可以干啥）
	- 管理员用户、学生用户、店家用户
- 用户管理模块（添加功能：注册、删除功能：登录后的所有用户、更新资料功能：登录后的所有用户）
	- 添加用户（区分用户身份：管理员用户、学生用户、店家用户）
	- 删除用户
	- 更新用户资料（姓名、性别、年龄、学号or工号、用户身份、电话号码等）
- 店家菜品管理页面（菜品属性：名称、原价格、折后价、销量等）（在店家用户登录后的页面可见）
	- 增加菜品（菜品属性：名称、原价格、折后价、销量等）
	- 删除菜品
	- 修改菜品属性（菜品属性：名称、原价格、折后价、销量等）
	- 查找菜品（名称、原价格、折后价、销量等）
- 学生评价模块
	- 提交评价（评分：5分满分&评语：文本框）
	- 学生投诉（提交给管理用户的文本框）
- 交易页面（在学生用户登录后的页面可见）
	- 提交订单（提交订单时间、购买菜品名、菜品数量、总价格、学生学号、学生电话等）
	- 完成付款（相关店家接收相应金钱、相关菜品销量增加）
	- 交付菜品（跳转个页面表示一下就可）
	- 售后服务（跳转学生评价模块）
- 收件箱（在店家、管理员登录后的页面可见）
	- 店家（接收学生评价）
	- 管理员（接收学生投诉）
- 店家收益总结页面（在店家用户登录后的页面可见）
	- 店家收入总和展示（数额）
	- 菜品的销量排名（显示销量）
- 学生支出总结页面（在学生用户登录后的页面可见）
	- 学生支出总和展示（数额）

![功能图](p1.png)

演示视频地址：[Onedrive](https://zong-my.sharepoint.com/:v:/g/personal/wenders_nekopara_net/Ed9T8ZvWiCFAt0Lmak-j0MUB8K78FFWkr8Kc_S4WwraMOA?e=EM8JuN)


## 运行环境
java 1.8.0

springboot 2.1.8.RELEASE

mysql 8.0.21


## 项目结构
```
.
├── database
│   └── spboot03966stglxt.sql
├── mvnw
├── mvnw.cmd
├── pom.xml
├── spboot.iml
├── src
│   └── main
│       ├── java
│       │   ├── com
│       │   │   ├── base
│       │   │   └── spring
│       │   │       ├── BootApplication.java
│       │   │       ├── config
│       │   │       │   └── AutoStartProjectInDefaultBrowser.java
│       │   │       ├── controller
│       │   │       ├── dao
│       │   │       ├── entity
│       │   │       ├── service
│       │   │       │   └── impl
│       │   │       └── util
│       │   ├── dao
│       │   └── util
│       ├── resources
│       │   ├── application.properties
│       │   ├── mapper
│       │   ├── static
│       │   └── templates
│       └── webapp
└── target
    ├── boot-0.0.1-SNAPSHOT.jar
    └── boot-0.0.1-SNAPSHOT.jar.original
```

**完整代码 +  QQ: 316595344     或   WX: lz316595344  咨询**

**接毕业设计和论文**