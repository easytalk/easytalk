

|--------------------------|
   系统安装步骤
|--------------------------|

1、【安装环境】需要php5.x、mysql5.x以上的服务器环境，绝大部分空间都支持；

2、【上传文件】通过FTP工具，将安装包解压出的全部文件使用二进制模式上传到空间上；

3、【目录权限】如果是linux系统主机请将以下目录和其下的所有文件属性修改为可读写（777）；
	./Home	
	./Home/Runtime	
	./Home/Runtime/Cache	
	./Home/Runtime/Data	
	./Home/Runtime/Logs	
	./Home/Runtime/Temp	
	./Admin	
	./Admin/Runtime	
	./Admin/Runtime/Cache	
	./Admin/Runtime/Data	
	./Admin/Runtime/Logs	
	./Admin/Runtime/Temp	
	./Public/attachments	
	./Public/attachments/usertemplates	
	./Public/attachments/usertemplates/themetemp	
	./Public/attachments/photo	
	./Public/attachments/head	
	./Public/attachments/downtheme	
	./Public/backup
	./Apps
	./api/uc_client/config.inc.php

4、【执行安装】在浏览器中访问http://你的微博域名，根据页面提示，系统即可自动完成安装；

5、【管理后台】管理后台的地址是admin.php，用你安装时候设置的管理员用户名和密码登录。
