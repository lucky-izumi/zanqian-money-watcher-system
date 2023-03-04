前言：本项目的目的是巩固练习所学习的java及spring的知识点。属于第一次完全独立设计和编写完整的web项目，并不是一个成熟的web项目，仅供参考。

项目地址:[安手账](http://antechou.lazyan.top/)

github:[lazyAN0/antechou](https://github.com/lazyAN0/antechou)

gitee:[ lazyAN / antechou](https://gitee.com/lazyan/antechou)

个人博客：[LuckyIzumi](https://luckyizumi.com//)

**所选技术栈：**

1. 框架：Springboot+mybatis
2. 数据库：mysql
3. 前端：thymeleaf+bootstrap+vue

**功能模块介绍：**

1. 用户功能模块
2. 记账功能模块

**用户功能模块**

```
包含用户登录，注册，编辑功能。

进入主页面是验证是否登入，未登录则跳转登录页面。在登录页面输入账号密码，验证登录之后跳转主页面。

在未登陆的时候在登录页面点击注册按钮，进入注册页面。输入唯一的账号密码，验证之后注册成功。注册成功后会随机生成用户名，以及默认的用户信息。

登录之后在主页面点击编辑按钮，会跳转到用户信息编辑页面。可以修改性别出生年月等信息。
```

**记账功能**

```
包含添加账单信息，编辑收支分类，收支统计功能。

在主页面点击添加按钮弹出添加账单页面，输入相关信息后添加成功。

在主页面编辑编辑账单分类的按钮跳转到分类编辑页面，添加或删除分类。

在主页面点击统计按钮跳转到账单统计页面，通过图表展示每月的账单分类按钮。
```

**数据库设计**

1. 账号表

   保存账号密码（后期可能改造成加密表）信息
   
2. 用户表

   保存用户名，性别，生日等信息。
   
3. Ip表

   保存登录ip和登陆时间的信息。
   
4. 账单表

   保存每次收入或支出信息。
   
5. 账单分类表

   保存账单的分类信息。
