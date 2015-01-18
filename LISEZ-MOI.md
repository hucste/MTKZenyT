MTKZenyT(ools)
==============

*(Project EN/FR !)*

Scripts Bash pour flasher MT6589 (tel que le Xiaomi Redmi) sous GNU/Linux.

Auteur
------

**HUC Stéphane** : <devs@stephane-huc.net><br />
*alias* : *[ATP:RedRice][1]*, *[ATP:MIUI][2]*, *[ATP][3]*
[1]: http://en.miui.com/index.php?192725708
[2]: http://forum.frandroid.com/user/1514-atpmiui/
[3]: http://www.freaktab.com/member.php?42437-ATP
<br />
*GIT* : <https://github.com/hucste/MTKZenyT><br />
*Licence* : CC0 http://directory.fsf.org/wiki/License:CC0

----

Cet outil fonctionne avec :

1. **adb tools** <br />
    - Pour *Buntu 13.04 >= (et assimilé), utilisez le dépôt PPA suivant :
    <https://launchpad.net/~phablet-team/+archive/tools>
2. **SuperSU** <br />
	- <http://www.chainfire.eu/> <br />
    - <http://download.chainfire.eu/supersu> <br />
	- <https://play.google.com/store/apps/details?id=eu.chainfire.supersu> <br />

*Il est possible d'utiliser les interfaces graphiques <b>dialog</b> ou <b>zenity</b>, si vous les installez.*

---

USAGE
-----

1. rendre le script MTK_Shell_Tools exécutable !
2. le lancez dans un terminal-console.
3. répondez aux questions :p

Le répertoire 'tools' est nécessaire pour déposer Archive ZIP SuperSU. Vous pouvez le décompresser ...

29/10/14 : Maintenant, il est possible d'utiliser l'outil en console avec des options.<br />
    Lancez-le avec l'option '--help' afin d'en savoir plus à ce propos.


Configuration
-------------

Il est possible de configurer le fichier 'config.ini'.<br />
Vous pouvez le renommer, mais dans ce cas-là, vous devrez changer la valeur correspondante dans le fichier /inc/config

**Paramètrages : **

1. **Pour afficher une interface graphique:** *Il faut changer la valeur de* **GUI**
    - dialog: `GUI=d` ou `GUI=dialog`
    - zenity: `GUI=z` ou `GUI=zenity`
    - no: `GUI=0` ou `GUI=no`
2. **Pour journaliser l'activité :** *Il faut changer la valeur de* **LOG**
    - `0` pour désactiver,
    - `1` pour activer.
3. **BCPK_PHONE** est la variable pour indiquer où créer les sauvegardes dans l'appareil.
4. **DIR_SVG** est la variable pour indiquer où sauvegarder sur votre ordinateur.


"Enjoy-IT!"
-----------

!!! C'est en phase de développement ! <br />
!!! Utilisez à vos risques et périls !!!

Forum
-----

Je peux certainement vous aider, autant que possible, en Français sur [FrAndroid][1], ou en Anglais sur [FreakTab][2]!

[2]: http://www.freaktab.com/showthread.php?17985-MT6589-%28Xiaomi-Redmi%29-Root-n-flash-under-Linux
[1]: http://forum.frandroid.com/topic/205201-redmi-1-outils-sous-linux/

"Ne demandez pas la Lune, non plus ! ;-)"
