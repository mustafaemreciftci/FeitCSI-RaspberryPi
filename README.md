# FeitCSI & FeitCSI-iwlwifi

This repository provides tools and drivers for working with **Channel State Information (CSI)** on supported Intel Wi-Fi devices and Raspberry Pi.  

---

## 📦 Prerequisites

Make sure your system is up to date and install the required dependencies.

```bash
git clone https://github.com/mustafaemreciftci/FeitCSI-RaspberryPi

sudo apt update
sudo apt install linux-headers-generic flex bison dkms

sudo apt update
sudo apt install libgtkmm-3.0-dev libnl-genl-3-dev libiw-dev libpcap-dev
```

### For `FeitCSI-iwlwifi`

```bash
cd FeitCSI-RaspberryPi
cd FeitCSI-iwlwifi

make defconfig-iwlwifi-public
make
sudo make install
```

### For `FeitCSI`

```bash
cd ../FeitCSI

make
sudo make install
```
