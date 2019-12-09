## 安装方法
服务端
wget https://raw.githubusercontent.com/CangShui/ServerStatus-Hotaru/master/status.sh && bash status.sh s


1、选择1，配置服务端

2、没什么需求的话，端口建议默认就好

3、如果本地没装别的如Nginx或者Apache之类的，直接Y就好

4、绑定域名或IP访问

5、端口自主选择

6、添加客户端：选择7后选1

剩下的信息自己填就好了

7、删除（修改）服务端：选7后在选择

客户端

wget https://raw.githubusercontent.com/CangShui/ServerStatus-Hotaru/master/status.sh && bash status.sh c


## 修改方法

配置文件：/usr/local/ServerStatus/server/config.json备份并自行添加Region

![](https://i.loli.net/2019/02/07/5c5bca12df8b0.png)

卸载ServerStatus-Toyo安装ServerStatus-Hotaru替换配置文件，重启ServerStatus

