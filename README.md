# DNF-server /台服DNF服务端
- 服务端系统请基于 Linux centos 5.8版本 进行搭建
- 上传 Package.tar install 文件到跟目录下并给予777权限
- 启动指令：cd /;chmod -R 0777 /install;bash install
- 虚拟内存设置建议为 8192MB
- IP为您的外网IP&内网IP
- 之后脚本会自动搭建完毕后会自动重启服务端系统
- 上传生成的你的密钥文件 publickey.pem
- [注：如果使用高于centos5系 6系7系及以上 需要附加如下操作]
- 关闭CPU高精度 重启生效
- grubby --update-kernel=ALL --args=highres=off 
- 补全安装支持库
- yum install -y xulrunner.i686
- yum install -y libXtst.i686
# 默认目录信息如下
- "启动服务端命令为“./run”，关闭命令为“./stop”"
- "数据库默认帐号为“game”"
- "数据库默认密码为“uu5!^%jg”"
- "php目录为：“/opt/lampp/htdocs"
- "数据库目录为“/opt/lampp/var/mysql”"
