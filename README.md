# 一 简介
这是移动互联网应用开发课程的第一个小项目---无人机新闻---的后台，采用了node.js11.13+mysql5.7架构，并采用了docker容器化。
# 二 使用方法
## 2.1 启动项目
在项目目录下执行    
```bash
docker-compose up --build -d
```
## 2.2 停止项目
在项目目录下执行
```bash
docker-compose down --volumes
```
## 2.3 API接口
### 2.3.1 建立数据表并自动插入数据
    http://127.0.0.1:3000/createTable
### 2.3.2 获取数据
    http://127.0.0.1:3000
### 2.3.3 删除数据
    http://127.0.0.1:3000/deleteData
# 三 相关信息
## 3.1 端口映射
   node.js 3000:3000  
   mysql 3306:3306
## 3.2 数据库信息  
   用户名：root 密码：123456
   数据库：news
