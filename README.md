# My pc setup

`sudo cp ./configs/30-touchpad.conf /etc/X11/xorg.conf.d/`

`sudo cp ./configs/99-disable-wireless-when-wired /etc/NetworkManager/dispatcher.d && sudo chmod +x /etc/NetworkManager/dispatcher.d/99-disable-wireless-when-wired`

`sudo cp ./configs/disable-turbo.sh /opt && sudo chmod +x /opt/disable-turbo.sh`

`sudo cp ./configs/disable-turbo.service /etc/systemd/system/`

`systemctl enable disable-turbo`

+install intel-undervolt

## Install manually

`yay -S spotify optimus-manager onlyoffice-bin timeshift`
