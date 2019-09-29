# rpigpio

sudo cp rpigpio/rtscts.dtbo /boot/overlays/

sudo vi /boot/config.txt 
// rtscts device tree
dtoverlay=rtscts  
// uart0 txd rxd 
disable_uart=0 

sudo rpigpio/gpio // HDMI distributor

//IMAGE viewer
sudo apt-get install fbi
sudo fbi -a -T 1 defense_img.png
