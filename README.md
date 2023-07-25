任务3-更新操作系统

`apt`

1.在“终端模式”中，列出所有可更新的软件清单

```
apt update
```

2.在“终端模式”中，静默方式升级所有可更新软件包
```
apt upgrade
```

在每小题下面截图体现出上述要求，截图数量不限

任务4-使用应用商店安装常用软件

1.使用“应用商店”，安装“微信”客户端

2.使用“应用商店”，安装“钉钉”客户端

3.使用“应用商店”，安装“腾讯会议”客户端

4.使用“应用商店”，安装“Foxmail”客户端

在每小题下面截图体现出上述要求，截图数量不限

任务5-使用软件包安装器安装常用软件

1.使用如下路径下载“VS Code”。下载路径：
```
wget https://az764295.vo.msecnd.net/stable/b06ae3b2d2dbfe28bca3134cc6be65935cdfea6a/code_1.69.1-1657615746_amd64.deb
```

2.使用“软件包安装器”，安装刚刚下载的“VS Code”

3.使用如下路径下载“搜狗拼音输入法”。下载路径：
```
wget https://ime.sogouimecdn.com/202207182258/2d79bf492126e5f413fd2e0dbe8508f5/dl/gzindex/1656597217/sogoupinyin_4.0.1.2800_x86_64.deb
```
4.使用“软件包安装器”，安装刚刚下载的“搜狗拼音输入法”

5.使用如下路径下载“网易云音乐”。下载路径：
```
wget https://d1.music.126.net/dmusic/netease-cloud-music_1.2.0_amd64_deepin_stable_20190424.deb
```

6.使用“软件包安装器”，安装刚刚下载的“网易云音乐”

在每小题下面截图体现出上述要求，截图数量不限

任务6-使用终端模式安装常用软件

1.使用如下路径下载“WPS Office 2019”。下载路径：
```
wget https://wps-linux-personal.wpscdn.cn/wps/download/ep/Linux2019/11664/wps-office_11.1.0.11664_amd64.deb
```
2.在“终端模式”中，安装刚刚下载的“WPS Office 2019”
```
apt install ./wps-office_11.1.0.11664_amd64.deb
```
3.使用如下路径下载“MindMaster”。下载路径：
```
wget https://www.edrawsoft.cn/2download/x86_64/mindmaster_9.0.4_cn.x86_64.deb
```
4.在“终端模式”中，安装刚刚下载的“MindMaster”
```
apt install ./mindmaster_9.0.4_cn.x86_64.deb
```

在每小题下面截图体现出上述要求，截图数量不限

任务7-使用终端模式安装Python并配置环境变量

1.在“终端模式”中，检查操作系统中现有版本的“Python” 
```
python 或 python -V 或者 which python
```
```
python3 或 python3 -V 或者 which python3
```
```
apt list --installed *python*
```
2.在“终端模式”中，卸载操作系统中现有的所有“Python”
```
apt remove python*
```
(ls *.docs)

3.使用如下路径下载“Python安装包”。下载路径：
```
wget https://repo.huaweicloud.com/python/3.9.9/Python-3.9.9.tar.xz
```
4在“终端模式”中，使用编译的方式安装刚刚下载的“Python” 

①解压
```
tar -Jxvf Python-3.9.9.tar.xz
```
```
tar -Zxvf tar.gz
```
②检查配置
```
cd Python-3.9.9
```
```
./configure
```
③编译
```
make
```
④安装
```
make install
```
5.在“终端模式”中，配置“Python”环境变量
```
mv /tmp/Python-3.9.9 /opt/

cd /etc/profile.d/
```
```
vim python.sh
```
```
export PATH=$PATH:/opt/Python-3.9.9
```
```
source /etc/profile
```
6.在“终端模式”中，验证当前操作系统中的“Python”版本

python3

在每小题下面截图体现出上述要求，截图数量不限

任务8-使用终端模式安装Pycharm Community

1.使用如下路径下载“Pycharm Community”。下载路径：https://download.jetbrains.com.cn/python/pycharm-community-2022.1.3.tar.gz
2.在“终端模式”中，安装“Pycharm Community” 
mv pycharm-community-2022.1.3 /opt/

3.启动“Pycharm Community”，在plugins中输入 chinese 中出现有chinese-language..并安装“中文语言包” 

4.在桌面创建“Pycharm Community”的快捷方式
在每小题下面截图体现出上述要求，截图数量不限
任务9-使用终端模式安装 JDK Java Development Kit） 并配置环境变量

1.在“终端模式”中，检查操作系统中现有版本的“JDK” 
java -version

2.在“终端模式”中，卸载操作系统中现有的所有“JDK”
apt list --installed *jdk*
apt remvoe openjdk*

3.使用如下路径下载“JDK安装包”。下载路径：https://repo.huaweicloud.com/java/jdk/13+33/jdk-13_linux-x64_bin.tar.gz

4.在“终端模式”中，安装刚刚下载的“JDK” 

tar -zxvf jdk-13_linux-x64_bin.tar.gz

mv jdk-18 /opt/

5.在“终端模式”中，配置“JDK”环境变量

vim /etc/profile.d/jdk.sh

填写

export PATH=$PATH:/opt/jdk-18/bin/

6.在“终端模式”中，验证当前操作系统中的“JDK”版本

java -version

在每小题下面截图体现出上述要求，截图数量不限

任务10-使用终端模式安装IntelliJ IDEA Community

1.使用如下路径下载“IntelliJ IDEA Community”。下载路径：https://download.jetbrains.com.cn/idea/ideaIC-2022.1.3.tar.gz

2.在“终端模式”中，安装“IntelliJ IDEA Community” 

3.启动“IntelliJ IDEA Community”，并安装“中文语言包” 

4.在桌面创建“IntelliJ IDEA Community”的快捷方式

在桌面复制一个现有的快捷方式

cp deepin-forum.desktop pycharm.desktop

vim pycharm.desktop

[Desktop Entry]

Conmment=deepin forum desktop file

可执行文件

Exec=/opt/pycharm-community-2022.1.3/bin/pycharm.sh

Name[zh]=pycharm

Type=Application

X-Deepin-Vendor=deepin

图标

Icon=/opt/pycharm-community-2022.1.3/bin/pycharm.png

在每小题下面截图体现出上述要求，截图数量不限



