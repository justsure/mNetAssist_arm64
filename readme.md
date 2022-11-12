linux下图形界面的网络调试助手mNetAssist,网上均为x86 amd处理器的.

想在arm64上使用,所以,自己down了源码编译了一遍,方便大家使用.

使用说明
  
  以下步骤仅在ubuntu/debian 内适用. 其他arm64系统 请做改动
  
安装:

1:在  /etc/ld.so.conf.d  目录下 添加mNetAssist.conf 文件

2:文件内容为 mNetAssist 的目录 例如/root/mNetAssist/

3:sudo ldconfig

4: 重启系统(不重启也可)


使用:
到mNetAssist目录下  执行 ./mNetAssist 或 nohup ./mNetAssist &


也可访问 看详细步骤:https://blog.csdn.net/justsure91/article/details/127817147?csdn_share_tail=%7B%22type%22%3A%22blog%22%2C%22rType%22%3A%22article%22%2C%22rId%22%3A%22127817147%22%2C%22source%22%3A%22justsure91%22%7D
