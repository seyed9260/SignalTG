```sh

# دستورات زیر را در ترمینال وارد کنید
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev
cd $HOME
git clone https://github.com/SIGNALTEAM/SignalTG.git
cd SignalTG
chmod +x launchfix2.sh
chmod +x launch.sh
chmod +x autolaunch.sh
chmod +x steady.sh
chmod +x sudo.sh
chmod +x launchs.sh
./launch.sh install
cd .luarocks
cd bin
./luarocks-5.2 install luafilesystem
./luarocks-5.2 install lub
./luarocks-5.2 install luaexpat
cd $HOME
cd SignalTG
./launch.sh install
./launch.sh # Enter a phone number & confirmation code.
```

**دستورات بالا را دقیق وارد کنید**

```
# آموزش اتولانچ :

killall screen
killall tmux
killall telegram-cli
tmux new-session -s script "bash sudo.sh -t"
```

# آموزش Launchs.sh :

**خوب Launchs.sh ابزار کاربردی مدیریت ربات هست مثلا میتونید باهاش بکاپ بگیرید و ...**

***برای لانچ کردنش هم دستور ./launchs.sh را در ترمینال وارد کنید***

** با تشکر **
