E2iPlayer Sony Player HU host

Install:

~~~
wget --no-check-certificate https://github.com/e2iplayerhosts/sonyplayer/archive/master.zip -q -O /tmp/sonyplayer.zip
unzip -q -o /tmp/sonyplayer.zip -d /tmp
cp -r -f /tmp/sonyplayer-master/IPTVPlayer/* /usr/lib/enigma2/python/Plugins/Extensions/IPTVPlayer
rm -r -f /tmp/sonyplayer*
~~~

restart enigma2 GUI
