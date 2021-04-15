# study_flask

## 后端
-- db.sql	创建数据库的 SQL 脚本文件  
-- app.py	Flask 应用程序实例以及配置  
-- main.py	Flask 应用程序的入口  
-- db.py	提供访问数据库的功能函数  
-- users.py	实现蓝图 users，提供登录、注册的功能  
-- todos.py	实现蓝图 todos，提供增加、修改、删除待做事项 todo 的功能  



      -- 数据库设计
         -- 表的设计
         -- 数据库脚本 db.sql

      -- Flask 实例 app.py
3. 入口 main.py
3.1 导入相关模块
3.2 页面 / 的视图函数
4. 数据库访问 db.py
4.1 引入相关模块并配置
4.2 映射表 users 和表 todos
4.3 对表 users 进行操作
4.4 对表 todos 进行操作
5. 蓝图 users.py
5.1 导入相关模块
5.2 登录表单
5.3 请求 /users/login 页面
5.4 注册表单
5.5 请求 /users/register 页面
5.6 退出系统 /logout
6. 蓝图 todos.py
6.1 导入相关模块
6.2 请求 /todos/add 页面
6.3 请求 /todos/update 页面
6.4 请求 /todos/delete 页面
7. 小结

## 前端
-- templates/index.html	首页的页面模板  
-- templates/login.html	登录的页面模板  
-- templates/register.html	注册的页面模板  

-- static/style.css	样式文件  

-- static/script.js	调用后端服务的接口  

## 程序结构
![image](https://user-images.githubusercontent.com/48540417/114809249-6783f800-9ddc-11eb-8a5b-21f09245bbd8.png)
