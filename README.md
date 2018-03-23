# transmission
适用于centos的transmission
=====
安装命令
---
wget https://raw.githubusercontent.com/alekkxl/transmission/master/transmission.sh && bash transmission.sh -u 帐号 -p 密码 --port 9091

停止命令
---
systemctl stop transmission-daemon.service
修改配置
---
vi /var/lib/transmission-daemon/info/settings.json
重新启动
---
systemctl start transmission-daemon.service