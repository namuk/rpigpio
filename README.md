# rpigpio

sudo cp rpigpio/rtscts.dtbo /boot/overlays/

sudo vi /boot/config.txt 

dtoverlay=rtscts  
// rtscts device tree

disable_uart=0 
// uart0 txd rxd 



sudo rpigpio/gpio // HDMI distributor

//IMAGE viewer

sudo apt-get install fbi

sudo fbi -a -T 1 defense_img.png
