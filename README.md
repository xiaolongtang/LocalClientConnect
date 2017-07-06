# LocalClientConnect
可以轻松使用本地客户端连接云数据库

# 使用方法

##### 1. 部署程序到云端
git clone https://github.com/xiaolongtang/LocalClientConnect.git 到你的本地。cd 到app路径底下，cf push到服务器。

##### 2. 安装客户端
从client 根目录下，把chisel.exe复制到c:\windows\system32 目录下。启动命令行工具，可以敲chisel命令查看是否安装成功

##### 3.创建连接
通过cf env 查看数据库信息。通过命令：
chisel client -v --keepalive 3s https://predix-chisel-postgres-undiametrical-lignocellulose.run.aws-usw02-pr.ice.predix.io 4000:db-9a067128-ea3e-4d68-be4b-7b76c3aa13ec.c7uxaqxgfov3.us-west-2.rds.amazonaws.com:5432

##### 4. 数据库客户端连接
- ip：localhost
- port：4000
- user name：云数据库用户名
- password：云数据库密码
