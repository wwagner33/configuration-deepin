# Graphical Adapter in Deepin

## Get GPU Info

Show informations about graphical adapter.
```bash

sudo lshw -C display -short


```
Install the packages:

```bash
sudo apt install acpica-tools mesa-utils
```

To probe your system better, use hw-probe:
1. Download the DEB: (https://github.com/linuxhw/hw-probe/releases/download/1.5/hw-probe_1.5-1_all.deb)[https://github.com/linuxhw/hw-probe/releases/download/1.5/hw-probe_1.5-1_all.deb]
2. 2. Install DEB on Deepin
```bash
sudo apt-get update
sudo dpkg -i ./hw-probe_1.5-1_all.deb
sudo apt-get install -f --no-install-recommends
```
