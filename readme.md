

```bash
# xmodmap -e "keycode  22 = BackSpace Delete BackSpace Delete"
# xmodmap -e "keycode  22 = BackSpace NoSymbol BackSpace"
xmodmap -e "keycode 118 = Delete NoSymbol Delete"
```

[HP](https://www8.hp.com/us/en/home.html)
* [HP EliteBook 820 G3](https://support.hp.com/us-en/product/hp-elitebook-820-g3-notebook-pc/7815289)
  * [drivers](https://support.hp.com/us-en/drivers/selfservice/hp-elitebook-820-g3-notebook-pc/7815289/model/7815292)

|Item|Version|Date|File|
|:-:|:-:|:-:|:-:|
|BIOS|01.45 Rev.A|Feb 10, 2020|sp101340.exe|
|Intel ME|11.8.70.3626 Rev.A|Sep 26, 2019|sp99429.exe|

[惠普(HP)授權服務中心](http://support.hpicss.com/ascindex_detail.aspx?Province=%e5%b9%bf%e4%b8%9c&city=%e6%b7%b1%e5%9c%b3%e5%b8%82&COUNTY=%e5%8d%97%e5%b1%b1%e5%8c%ba&PRODUCTLIST=%e7%ac%94%e8%ae%b0%e6%9c%ac%e5%8f%8a%e9%85%8d%e4%bb%b6)  
[深圳市南山區深南大道12069號海岸時代公寓東座3108](https://j.map.baidu.com/4a/S10)  
0755-83261368 8003  
0755-83246625  
週一至週日09:00-18:00

https://wiki.archlinux.org/index.php/HP_EliteBook_2560p#Cardreader

pointing stick
```bash
xinput list
xinput list-props 'PS/2 Generic Mouse'
```

[rescan audio devices](https://superuser.com/a/869229/)
```bash
pacmd unload-module module-udev-detect
pacmd load-module module-udev-detect
```
