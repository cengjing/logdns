log dns  php java


---

unixbench.sh

---


wget http://logdns.googlecode.com/files/unixbench.sh

sh unixbench.sh



---

centos transmission

wget https://logdns.googlecode.com/files/pt-install.sh

sh pt-install.sh

your ip:2020

user:logdns

passwd:logdns

注意：在修改前先把Transmission服务给停止掉，编辑完成然后再启动：

停止服务：service transmissiond stop


启动服务：service transmissiond start


编辑 user and passwd in /home/transmission/.config/transmission/settings.json

rpc-port 端口

rpc-username 用户名

rpc-password 密码



需要win软件管理的下载Transmission Remote GUI

https://transmisson-remote-gui.googlecode.com/files/transgui-4.1-setup.exe


---

centos6  vpn bash

wget https://logdns.googlecode.com/files/cs6_vpn.sh

chmod a+x cs6\_vpn.sh

bash cs6\_vpn.sh

然后按照提示选择，上面的是x86的

x64的直接替换

https://logdns.googlecode.com/files/ppp-2.4.5-17.0.rhel6.x86_64.rpm

https://logdns.googlecode.com/files/pptpd-1.3.4-2.el6.x86_64.rpm



---
