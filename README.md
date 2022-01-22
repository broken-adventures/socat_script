# 基于socat的一键端口转发脚本

系统要求：支持CentOS 6+ 、Debian 7+、Ubuntu 14+  

脚本说明：脚本默认同时开启TCP、UDP转发，且带开机自启功能，每次运行可配置一个端口转发，如果想转发多个端口请重复运行本脚本。  

使用教程：  
root账号运行以下命令  
```
wget https://raw.githubusercontent.com/ycyw/socat_script/main/socat_script.sh && bash socat_script.sh  
```
按要求输入本地服务器端口，要转发的目标端口和服务器IP即可！  
