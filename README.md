使用帮助
---
1.执行安装脚本
```
wget https://raw.githubusercontent.com/qinghuas/ss-panel-and-ss-py-mu/master/v3.sh;chmod 777 v3.sh;bash v3.sh
```
若提示：`-bash: wget: command not found`，则
Centos：`yum -y install wget `
Debian/Ubuntu：`apt-get install wget`

其他帮助
---
1.执行命令`supervisorctl restart ssr`提示`unix:///tmp/supervisor.sock no such file`  
答：执行`/usr/bin/supervisord -c /etc/supervisord.conf`
