#powered by javapms

http://www.wooyun.org/bugs/wooyun-2010-077395  头像Getshell
http://www.wooyun.org/bugs/wooyun-2010-067865 存储型跨站结合CSRF可获取管理员权限+后台Getshell
http://drops.wooyun.org/tips/662  获取Jspx 菜刀shell、

admin/login.do 后台管理
login.jsp      登录
reg.jsp        注册
/member/index.jsp  个人中心
/member/editInfo.jsp 修改头像

必须使用jspx
更改context-type： image/jspx

/webapps/ROOT/WEB-INF/config/jdbc/jdbc.properties

默认密码: admin javapms
	  test 123123
	  demo demo
	  javapms a123123
	  korven  123123

Content-Disposition: form-data; name="file"; filename="java.jspx"
Content-Type: image/jspx

