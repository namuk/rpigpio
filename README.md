# rpigpio

sudo cp rpigpio/rtscts.dtbo /boot/overlays/

sudo vi /boot/config.txt 
++dtoverlay=rtscts  
++disable_uart=0 
// rtscts device tree
// uart0 txd rxd 

sudo rpigpio/gpio // HDMI distributor

//IMAGE viewer
sudo apt-get install fbi
sudo fbi -a -T 1 defense_img.png
