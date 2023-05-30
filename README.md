# MKSDEB
1. 在板子上登录到命令台  
2. 下载打包源码：  
git clone https://github.com/MS1987/QIPANG_DEB.git   
3. 在下载下来的源码中修改自己的内容，比如配置文件在：MKSDEB/home/mks/printer_data/config/路径下，可以直接用nano来修改，如：
nano MKSDEB/home/mks/printer_data/config/printer.cfg
或者
nano MKSDEB/home/mks/printer_data/config/MKS_THR.cfg
5. 修改完，切换到MKSDEB上一级目录，并运行
chmod 775 MKSDEB/DEBIAN/*  
dpkg -b MKSDEB armbian-update.deb 
把armbian-update.deb包弄出来就可以了
