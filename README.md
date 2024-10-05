---
### 👉作者QQ ：1556708905 微信：zheng0123Long (支持修改、部署调试、定制毕设)

### 👉接网站建设、小程序、H5、APP、各种系统等

### 👉选题+开题报告+任务书+程序定制+安装调试+ppt 都可以做
---

**博客地址：
[https://blog.csdn.net/2303_76227485/article/details/136288869](https://blog.csdn.net/2303_76227485/article/details/136288869)**

**视频演示：
[https://www.bilibili.com/video/BV1NA4m1F79q/](https://www.bilibili.com/video/BV1NA4m1F79q/)**

**毕业设计所有选题地址：
[https://github.com/zhengjianzhong0107/allProject](https://github.com/zhengjianzhong0107/allProject)**

## 基于Java+Springboot+thymeleaf的物业管理系统(源代码+数据库+12000字论文+开题+ppt)129

## 一、系统介绍
本系统分为管理员、小区管理员、用户三种角色

### 1、用户：
- 登录、车位费查询、物业费查询、公告通知、评论、投诉服务、报修服务、个人中心、密码修改
### 2、小区管理员：
- 车位费管理、物业收费管理(收费项目管理、抄表管理、缴费记录管理)、投诉管理、报修管理、维修管理、密码修改
### 3、超级管理员：
- 小区管理员所有功能、住户管理、楼宇管理、房屋管理(出售、出租)、车位管理、员工管理、统计分析、公告管理、公告评论管理、投诉信息管理、保修信息管理

## 二、所用技术

后端技术栈：

- Springboot
- Mybatis
- Mysql
- Maven

前端技术栈：

- thymeleaf 
- html
- ajax 
- css
- javascript
- layui

## 三、环境介绍

基础环境 :IDEA/eclipse,navicat, JDK1.8, Mysql5.7及以上,Maven3.6

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图
### 1、用户
![contents](./picture/picture1.png)
![contents](./picture/picture2.png)
![contents](./picture/picture0.png)
![contents](./picture/picture3.png)
![contents](./picture/picture4.png)
![contents](./picture/picture5.png)
![contents](./picture/picture6.png)
![contents](./picture/picture7.png)
![contents](./picture/picture8.png)
![contents](./picture/picture9.png)
![contents](./picture/picture10.png)
![contents](./picture/picture11.png)

### 2、社区管理员：
![contents](./picture/picture13.png)
![contents](./picture/picture14.png)
![contents](./picture/picture15.png)
![contents](./picture/picture16.png)
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)
![contents](./picture/picture19.png)

### 3、超级管理员：
![contents](./picture/picture20.png)
![contents](./picture/picture21.png)
![contents](./picture/picture22.png)
![contents](./picture/picture23.png)
![contents](./picture/picture24.png)
![contents](./picture/picture25.png)
![contents](./picture/picture26.png)
![contents](./picture/picture27.png)
![contents](./picture/picture28.png)
![contents](./picture/picture29.png)
![contents](./picture/picture30.png)
![contents](./picture/picture31.png)
![contents](./picture/picture32.png)
![contents](./picture/picture33.png)
![contents](./picture/picture34.png)
![contents](./picture/picture35.png)
![contents](./picture/picture36.png)
![contents](./picture/picture37.png)
![contents](./picture/picture38.png)

## 五、浏览地址

前台访问地址：http://localhost:2281/housing/index
- 用户账号/密码：张三/123456

后台访问地址：http://localhost:2281/housing/system/toLoginPage
- 小区管理员账号/密码：wyadmin/123456
- 超级管理员账号/密码：admin/123456

## 六、部署教程
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql文件
2. 使用IDEA/Eclipse导入community_estate_manage项目，若为maven项目请选择maven，等待依赖下载完成
3. 进入src/main/resources修改application.yml里面的数据库配置
4. src/main/java/com/project/property/PropertyAdminApplication.java启动后端项目

