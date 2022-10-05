Ubuntu R8125网卡驱动离线安装

问题描述：

1.电脑连接以太网，使用Windows系统时正常上网

2.使用Ubuntu系统时不能上网且没有图标

可以使用以上离线安装包进行安装，文件夹结构如下图所示：

<img title="" src="file:///C:/Users/ADMIN/AppData/Roaming/marktext/images/2022-10-05-18-58-32-image.png" alt="" width="397">

依次进入gcc、make、build-essential目录，执行命令

sudo dpkg -i *.deb

进行安装

安装完成之后，进入r8125-9.007.01文件夹，执行命令

sudo chmod +x autorun.sh
sudo sh ./autorun.sh

完成安装。
