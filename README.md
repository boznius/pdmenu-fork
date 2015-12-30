# pdmenu-fork
pdmenu-fork

# installation centos / rhel / amazon linux
yum install slang-devel
git clone 
cd pdmenu-fork

# Default binary location
/usr/local/bin/pdmenu

# Default rc menu location
/usr/local/etc/pdmenurc

# personalize menu per user 
cp /usr/local/etc/pdmenurc /home/exampleuser/.pdmenurc
then edit /home/exampleuser/.pdmenurc

# Using as user login shell
exampleuser:x:510:511::/home/exampleuser:/usr/local/bin/pdmenu

