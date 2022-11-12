使用说明
  
  以下步骤仅在ubuntu/debian 内适用. 其他arm64系统 请做改动
  
安装:

1:在  /etc/ld.so.conf.d  目录下 添加mNetAssist.conf 文件

2:文件内容为 mNetAssist 的目录 例如/root/mNetAssist/

3:sudo ldconfig

4: 重启系统(不重启也可)


使用:
到mNetAssist目录下  执行 ./mNetAssist 或 nohup ./mNetAssist &
