# transmission
适用于centos的transmission
=====
##安装命令

<br/>wget https://raw.githubusercontent.com/alekkxl/transmission/master/transmission.sh && bash transmission.sh -u 帐号 -p 密码 --port 9091
</br>
##停止命令

<br/>systemctl stop transmission-daemon.service</br>
##修改配置

<br/>vi /var/lib/transmission-daemon/info/settings.json</br>
##重新启动

<br/>systemctl start transmission-daemon.service</br>