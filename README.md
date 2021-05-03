# RaspberryPi_Bluetooth_and_Serial

First of all: sudo raspi-config > to enable the hardware for serial comunication 
NO to enable login by serial and YES for hardware activation

Then Reboot

# Libraries
## For Bluetooth
sudo apt-get install -y bluetooth &&
sudo apt-get install -y libbluetooth-dev &&
sudo apt-get install -y libsz2 libatlas3-base libjasper1 &&
sudo pip3 install pybluez -y

## For Serial
