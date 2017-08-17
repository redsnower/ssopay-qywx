# qywx
企业微信的项目

## 项目介绍

　　可以简单的把本项目看作[@fastadmin](https://gitee.com/karson/fastadmin)的java实现版本，目前主要实现了用户、角色（群组）和规则（菜单）管理，后续将实现一个企业微信的管理系统。

### 组织结构

```
ssopay-qywx
├── ssopay-qywx-common -- 公共模块，一些工具类及常量定义
├── ssopay-qywx-bean -- 数据库对应的实体类
├── ssopay-qywx-dao -- MyBatis DAO
├── ssopay-qywx-admin -- 后台管理
├── ssopay-qywx-web -- 前台界面，暂未实现
```

### 技术选型

#### 后端技术:
技术 | 名称 | 官网
----|------|----
Spring Framework | 容器  | [http://projects.spring.io/spring-framework/](http://projects.spring.io/spring-framework/)
SpringMVC | MVC框架  | [http://docs.spring.io/spring/docs/current/spring-framework-reference/htmlsingle/#mvc](http://docs.spring.io/spring/docs/current/spring-framework-reference/htmlsingle/#mvc)
Apache Shiro | 安全框架  | [http://shiro.apache.org/](http://shiro.apache.org/)
MyBatis | ORM框架  | [http://www.mybatis.org/mybatis-3/zh/index.html](http://www.mybatis.org/mybatis-3/zh/index.html)
Maven | 项目构建管理  | [http://maven.apache.org/](http://maven.apache.org/)

#### 前端技术:
技术 | 名称 | 官网
----|------|----
jQuery | 函式库  | [http://jquery.com/](http://jquery.com/)
Bootstrap | 前端框架  | [http://getbootstrap.com/](http://getbootstrap.com/)
Bootstrap-table | Bootstrap数据表格  | [http://bootstrap-table.wenzhixin.net.cn/](http://bootstrap-table.wenzhixin.net.cn/)
Font-awesome | 字体图标  | [http://fontawesome.io/](http://fontawesome.io/)

## 界面演示
### 登录页
![登录页](http://7xsmaf.com1.z0.glb.clouddn.com/login.png "登录页")
![控制台](http://7xsmaf.com1.z0.glb.clouddn.com/1.png "控制台")
### 用户管理
![用户管理](http://7xsmaf.com1.z0.glb.clouddn.com/2.png "用户管理")
![新增修改](http://7xsmaf.com1.z0.glb.clouddn.com/add.png "新增修改")
### 群组管理
![群组管理](http://7xsmaf.com1.z0.glb.clouddn.com/3.png "群组管理")
![新增修改](http://7xsmaf.com1.z0.glb.clouddn.com/add2.png "新增修改")
### 规则管理
![规则管理](http://7xsmaf.com1.z0.glb.clouddn.com/4.png "规则管理")
![新增修改](http://7xsmaf.com1.z0.glb.clouddn.com/add3.png "新增修改")

## 许可证

[Apache2](LICENSE "Apache2")