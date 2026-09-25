## Pre-req

Install `wrmsr` command.

### CachyOS 

```sh
# arch / cachyos
sudo pacman -S msr-tools

# ubuntu / debian
sudo apt install msr-tools
```


## Install

Copy the systemctl service file to:

```bash
sudo cp unlock-throttle.service /etc/systemd/system/unlock-throttle.service

# enable with:

sudo systemctl daemon-reload
sudo systemctl enable --now unlock-throttle.service
```
