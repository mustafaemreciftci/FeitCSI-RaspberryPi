FeitCSI-iwlwifi:

sudo apt install linux-headers-generic flex bison dkms

git clone https://github.com/mustafaemreciftci/FeitCSI-RaspberryPi

cd FeitCSI-iwlwifi

make defconfig-iwlwifi-public
make
sudo make install

FeitCSI:

sudo apt install libgtkmm-3.0-dev libnl-genl-3-dev libiw-dev libpcap-dev

cd FeitCSI
make
sudo make install
