MTKZenyT(ools)
==============

*(EN/FR project!)*

Scripts Bash to flash MT6589 (as Xiaomi Redmi) under Linux.

Author
------

**HUC Stéphane** : <devs@stephane-huc.net><br />
*alias* : *[ATP:RedRice][1]*, *[ATP:MIUI][2]*, *[ATP][3]*
[1]: http://en.miui.com/index.php?192725708
[2]: http://forum.frandroid.com/user/1514-atpmiui/
[3]: http://www.freaktab.com/member.php?42437-ATP
<br />
*GIT* : <https://github.com/hucste/MTKZenyT>

----

This tool use :

1. **adb tools** <br />
    - For *Buntu 13.04 >= (and like), use PPA:
    <https://launchpad.net/~phablet-team/+archive/tools>
2. **SuperSU** <br />
	- <http://www.chainfire.eu/> <br />
    - <http://download.chainfire.eu/supersu> <br />
	- <https://play.google.com/store/apps/details?id=eu.chainfire.supersu> <br />

*It's possible to use <b>dialog</b> or <b>zenity</b>, if you have installed them.*

---

USE
---

1. make script MTK_Shell_Tools executable!
2. run-it in terminal-console.
3. answer questions :p

Directory 'tools' is necessary to put Archive ZIP SuperSU. You can unzip her into...

29/10/14: Now, you can use tool into console with options. <br />
    Launch-it with --help to know more.

Config
------

It's possible to use file config, named 'config.ini'.<br />
You can rename-it, but in this case, change value into script bash /inc/config

**To use:**

1. **To display a GUI:** *Change value of **GUI***
    - dialog: `GUI=d` or `GUI=dialog`
    - zenity: `GUI=z` or `GUI=zenity`
    - no: `GUI=0` or `GUI=no`
2. **To log activities:** *Change value of **LOG***
    - `0` to disable,
    - `1` to enable.
3. **BCPK_PHONE** is variable to indicate where create backups into your phone.
4. **DIR_SVG** is variable to indicate where pull backups into your computer.


Enjoy-it!
---------

!!! It's still into development !!! <br />
!!! Use at yours personals risks !!!

Forum
-----

I can help you sometimes, asap, in French onto [FrAndroid][1], or in English onto [FreakTab][2]!

[2]: http://www.freaktab.com/showthread.php?17985-MT6589-%28Xiaomi-Redmi%29-Root-n-flash-under-Linux
[1]: http://forum.frandroid.com/topic/205201-redmi-1-outils-sous-linux/

