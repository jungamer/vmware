# vmware
## 主机与虚拟机之间复制粘贴文件以及复制粘贴文字
1. `https://slj666.blog.csdn.net/article/details/107603859?spm=1001.2101.3001.6650.1&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-1-107603859-blog-125015225.pc_relevant_aa&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-1-107603859-blog-125015225.pc_relevant_aa&utm_relevant_index=2`

2. `https://blog.csdn.net/llad2/article/details/125015225?utm_medium=distribute.pc_feed_404.none-task-blog-2~default~BlogCommendFromBaidu~Rate-1-125015225-blog-null.pc_404_mixedpudn&depth_1-utm_source=distribute.pc_feed_404.none-task-blog-2~default~BlogCommendFromBaidu~Rate-1-125015225-blog-null.pc_404_mixedpud`  

## 虚拟机联网  
1. 第二步：进入存放修改IP地址的目录：  

cd /etc/sysconfig/network-scripts/  
第三步：修改ip地址的文件：  
vim ifcfg-ens33  
第四步：修改静态IP地址和网关    
    修改BOOTPROTO=static
    添加以下内容：IP地址、子网掩码、网关、dns服务器
    IPADDR=192.168.75.100
    GATEWAY=192.168.75.2
    NETMASK=255.255.255.0
    DNS1=218.4.4.4
    DNS2=8.8.8.8
————————————————
版权声明：本文为CSDN博主「茂茂  呀」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/weixin_57258127/article/details/126057062
