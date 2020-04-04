# DST_DEDICATED_SERVER_CENTOS.md

```sh
sudo yum -y update
sudo yum -y install mlocate
sudo updatedb
sudo yum -y install sudo
sudo yum -y install glibc.i686 libstdc++.i686

sudo useradd steam
sudo usermod -aG wheel steam
sudo passwd steam
su - steam
mkdir ~/Steam && cd ~/Steam

curl -sqL "https://steamcdn-a.akamaihd.net/client/installer/steamcmd_linux.tar.gz" | tar zxvf -

sudo yum -y install tmux screen -y

./steamcmd.sh
login anonymous
force_install_dir ./dst_dedicated_server
app_update 343050 validate
./steamcmd.sh +login anonymous +force_install_dir ./dst_dedicated_server +app_update 343050 validate +quit

cd /home/steam/Steam/dst_dedicated_server/bin
./dontstarve_dedicated_server_nullrenderer
```

-port
-tick 60
-players 8
-console
