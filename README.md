## Preferred on Ubuntu

```bash
sudo apt-get install cups-pdf
```

![](https://github.com/xiangp126/gnome-manual-duplex/blob/master/img/pageSetup.png)

## gnome-manual-duplex
linux printer manual duplex under Ubuntu

https://sourceforge.net/projects/g-manual-duplex/files/

on Ubuntu:

dpkg -i xx.deb

sudo apt-get install -f

or manual compile,

## Compile Manually

sudo apt-get install transfig python-gtk2-dev

make -j

./gnome-manual-duplex

sudo make install

    Using the Gnome 3 Shell GUI:
	1)	$ gnome-session-properties
		Startup Programs -> GnomeManualDuplex -> Enable
		[logout][login]
	2)	Print -> GnomeManualDuplex (Virtual Printer) -> Print

## Whole Readme Page

Requires:
    psutils
	# dnf install psutils	-OR-	$ sudo apt-get install psutils
    file
	# dnf install file	-OR-	$ sudo apt-get install file
    gamin-python / python-gamin
	# dnf install gamin-python -OR-	$ sudo apt-get install python-gamin

Download and unpack:
    https://sourceforge.net/projects/g-manual-duplex/files/

    $ tar zxf gnome-manual-duplex.tar.gz
    $ cd gnome-manual-duplex

Install:
    $ make
    $ su
    # make install		-OR-	$ sudo make install
    [logout]
    [login]

Then:
    Using the Gnome 2 or Gnome-3 Classic (fallback) GUI:
	1a)	System Tools -> Gnome Manual Duplex
		- OR -
	1b)	Add to Panel -> Gnome Manual Duplex applet -> Add
	2)	Print -> GnomeManualDuplex (Virtual Printer) -> Print

    Using the Gnome 3 Shell GUI:
	1)	$ gnome-session-properties
		Startup Programs -> GnomeManualDuplex -> Enable
		[logout][login]
	2)	Print -> GnomeManualDuplex (Virtual Printer) -> Print

	If gnome-session-properties does not exist (Gnome 3.12+), you can
	install it with:
		$ gmd-autostart-3
		[logout][login]

    Works with *.ps and *.pdf files.
    Works with Gnome-2 or Gnome-3.

Works with:
    HP LaserJet 1000/1005/1018/1020/1022
    HP LaserJet Pro P1102/P1566
    HP LaserJet P1005/P1006/P1505
    HP Color LaserJet 1600/2600n/CP1215
    Minolta/QMS magicolor 2300 DL

Howto (video):
    http://www.youtube.com/watch?v=c4Ghomz6RQI

Translations:
    http://www.transifex.net/projects/p/gnome-manual-duplex/resource/messagespot
    http://crowdin.net/project/gnome-manual-duplex
    http://translationproject.org/domain/gnome-manual-duplex.html

Subversion Access:
    svn co \
	svn://svn.code.sf.net/p/g-manual-duplex/code/ \
	gnome-manual-duplex

    svn co \
	--username=USERNAME \
	https://svn.code.sf.net/p/g-manual-duplex/code/ \
	gnome-manual-duplex-code
