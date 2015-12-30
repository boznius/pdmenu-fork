# pdmenu-fork
pdmenu-fork

# installation centos / rhel / amazon linux
yum install slang-devel


git clone https://github.com/bbozhev/pdmenu-fork.git 


cd pdmenu-fork 


./configure && make && make install

# Default binary location
/usr/local/bin/pdmenu

# Default rc menu location
/usr/local/etc/pdmenurc

# personalize menu per user 
cp /usr/local/etc/pdmenurc /home/exampleuser/.pdmenurc
then edit /home/exampleuser/.pdmenurc

# Using as user login shell
exampleuser:x:510:511::/home/exampleuser:/usr/local/bin/pdmenu

