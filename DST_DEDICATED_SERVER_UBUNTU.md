# DST_DEDICATED_SERVER_UBUNTU.md

```sh
sudo apt-get update
sudo apt-get upgrade


sudo add-apt-repository multiverse
sudo dpkg --add-architecture i386
sudo apt update
sudo apt install lib32gcc1 steamcmd 

ln -s /usr/games/steamcmd steamcmd

mkdir ~/Steam && cd ~/Steam
curl -sqL "https://steamcdn-a.akamaihd.net/client/installer/steamcmd_linux.tar.gz" | tar zxvf -

steamcmd
login anonymous

force_install_dir ./dst_dedicated_server
```
