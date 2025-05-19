# Installations

## Nvidia NVL Drivers Installation : 

```
sudo apt search nvidia-driver
sudo apt search nvidia-fabricmanager
```
#### Find the Version which has both nvidia-driver & nvidia-fabricmanager

```
sudo apt-get install nvidia-driver-570
sudo apt-get install nvidia-fabricmanager-570
```

### To Update Nvidia Public Keys 
```
sudo apt-key adv --fetch-keys https://developer.download.nvidia.com/compute/cuda/repos/ubuntu1804/x86_64/3bf863cc.pub
sudo apt-key adv --fetch-keys https://developer.download.nvidia.com/compute/machine-learning/repos/ubuntu1804/x86_64/7fa2af80.pub
```

### To Update Nvidia Drivers Info in apt manager 
```
sudo add-apt-repository ppa:graphics-drivers/ppa
sudo apt update
```
