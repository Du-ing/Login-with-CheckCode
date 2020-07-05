# Servlet_Request_login
A Web Login prgramming by JavaEE

## 用户登录案例功能需求
1. 编写login.html登录页面
2. username&password两个输入框
3. 使用Druid数据库连接池技术，操作MySQL，duing数据库中的user表
4. 使用JdbcTemplate技术封装JDBC
5. 登陆成功跳转到SuccessServlet展示：登陆成功！用户名，欢迎您
6. 登陆失败跳转到FailServlet展示：登录失败！用户名或密码错误