# Java视频点播网站

> 学习过程中，遇到问题可以咨询作者。

### 演示地址

前台地址：  http://video.gitapp.cn

后台地址： http://video.gitapp.cn/admin

后台管理帐号：

用户名：admin123
密码：admin123

### 功能介绍

平台采用B/S结构，后端采用主流的Springboot框架进行开发，前端采用主流的Vue.js进行开发。

整个平台包括前台和后台两个部分。

- 前台功能包括：首页、视频列表、视频详情页、交互中心、个人中心模块。
- 后台功能包括：总览、视频管理、分类管理、标签管理、评论管理、用户管理、运营管理、日志管理、系统信息模块。

### 适合人群

大学生、系统设计人员、课程作业



### 代码结构

- server目录是后端代码
- web目录是前端代码

### 部署运行

#### 后端运行步骤

(1) 下载代码后，使用IntelliJ IDEA打开server目录

(2) 配置application.yml文件，配置数据库和upload根目录

(3) 安装mysql 5.7数据库，并创建数据库，创建SQL如下：
```
CREATE DATABASE IF NOT EXISTS xxx DEFAULT CHARSET utf8 COLLATE utf8_general_ci
```
(4) 恢复sql数据。在mysql下依次执行如下命令：

```
mysql> use xx;
mysql> source D:/xxx/xxx/xxx.sql;
```

(5) 启动后端服务：点击IDEA顶部run按钮


#### 前端运行步骤

(1) 安装node 16.14

(2) cmd进入web目录下，安装依赖，执行:
```
npm install 
```
(3) 运行项目
```
npm run dev
```


### 界面预览

首页

![](https://raw.githubusercontent.com/geeeeeeeek/java_video/master/server/upload/image/a.png)


后台页面
 
![](https://raw.githubusercontent.com/geeeeeeeek/java_video/master/server/upload/image/b.png)


### 待完善功能

- 邮箱推送功能
- 手机号绑定功能
- 粉丝关注功能
- 支付功能

### 付费咨询

微信：lengqin1024

