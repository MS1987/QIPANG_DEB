# MKSDEB
git clone -b qipang https://github.com/MS1987/MKSDEB.git   
chmod 775 MKSDEB/DEBIAN/*  
dpkg -b MKSDEB armbian-update.deb 
