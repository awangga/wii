Here is "Pimp My Wii", an homebrew that will Hack your Wii, install missing or outdated IOS / titles, install the cIOS and mIOS necessary.
The program will detect missing or outdated IOS and check that you have the latest version of the Wii System Menu. It also checks if you have the latest versions of BC, MIOS and those channels : Wii Shop, News, Weather, Mii, Photo and Photo 1.1
If you don't have the latest versions of those titles, the program will download them, or read them from USB or SD to install them. When using this program, you will have all advantages from 4.1 cumulated from those of 3.2, and this without drawbacks !
It also install cIOS d2x (based on Waninkoko) (249, 250) v8 and cIOS from Hermes 202/222/223/224 rev5.1. You can if you want install the cIOS from Waninkoko rev20/21 or d2x v6, 7 or 9beta (you'll have to install it manually from the menu "Install cIOS").
Pimp install the cMIOS from WiiGator.

Pimp will avert you if some homebrews aren't updated. Pimp check the version of the following homebrew (the dirnames must match, and are not case sensible) :
-> Neogamma, in version R9 beta 50 minimum. Dirname : neogamma
-> Usb Loader gx, in version 2.2 minimum. Dirname : usbloader_gx
-> Uloader, in version 5.1 minimum. Dirname : uloader
-> Wiiflow, in version 2.2 (or r302) minimum. Dirname : wiiflow
-> Configurable usb loader, in version 70 minimum. Dirname : usbloader or usbloader_cfg
Pimp does not update those homebrews itself. No verification will be made on channels, only on the files installed on the SD card in the directory /apps/.

The homebrew is displayed automatically in english, french, italian, german or spanish depending of your Wii's language. It is also compatible with NTSC-U, NTSC-J and PAL Wii consoles. (Korean Wii theoricaly compatible).
Warning: I do not take any responsibility for any damage in your wii because of a improper usage of this software.

Menu:
- Pass the test and fix problems
Check if everything is alright on the Wii, and install what need to be installed, after asking user.
- Pass the test
Only check if everything is alright on the Wii, without installing anything.
- Manual installation
Will propose to install every IOS and titles possible.. By default, the installation will be on "no".
- Hack te Wii/Minimal installation
Pass the test and only install the minimal requirement to hack your Wii. It patch IOS 36.
Also install the cIOSes 249, 250, 202, 222, 223, 224 from d2x and Hermes and the cMIOS.
- Install cIOS
Install a cIOS of your choice between cIOS from Hermes, Waninkoko and Waninkoko d2x. You can choose the IOS source of your choice, the destination slot and the revision.
For Waninkoko's/d2x cIOS, you can choose this IOS source: IOS36 v3607 IOS37 v5662 IOS38 v4123 IOS53 v5662 IOS55 v5662 IOS56 v5661 IOS57 v5918 IOS58 v6175 IOS60 v6174 IOS61 v5661 IOS70 v6687 IOS80 v6943 (IOS 58 only for revision above 20).
For Hermes cIOS, you have the choice between IOS60 v6174, IOS38 v3867, IOS37 v3869 and IOS57 v5661.

Button "minus", "safe mode". In this mode, the IOS test is disabled, you will be asked instead to choose an IOS to use for the installation. You must know that in this mode, you will not know if your installed IOS have the differents bugs, and then the program will not know if they need to be patched.


----------------------------------------------------
--------Correction of encountered problems----------
----------------------------------------------------
Here is a lit of common problems that you could have on your Wii (even on latest version) and the solutions that "Pimp My Wii" will do.

- Black screen at loading of dvd games :
Missing IOS -> Install those IOS (patching them)

- The Wii asks for an upgrade when inserting games :
Old IOS -> Update those IOS (patching them).

- A modified game (trucha signed) can't load on the disc channel with my modchip :
The IOS used by game has the trucha bug corrected -> Install a new IOS and patch the bug inside.
The IOS used by system menu has the trucha bug corrected -> Install a new IOS and patch the bug inside.

- The preloader and other homebrew does not work :
The IOS36 has the ES_Identify patched -> Install a new IOS 36 and patch the bug.

- I got reading problems with my backup launcher :
Old cIOS installed (older than rev20) -> Ask user to update this.

- No SD menu, no latest functionnality :
Old version of Wii (system menu, by example 3.2) -> Upgrade to 4.1 (but patching everything) for more compatibility, functionnality.

- The Wii Shop ask me to update :
Old version of Wii Shop (older than v20) -> Upgrade to this version (and install IOS 56 associated).

- I don't have any IOS that has the trucha bug (if you have a virgin Wii) :
The homebrew put the trucha bug back in IOS15.

- I can't install the Hackmii Install, because I have some kind of cIOSCorp :
You need a unmodified IOS 58 -> Install this IOS.

!!!!!!!!!Leave the parameters by default if you don't know what you do ! A bad choice of "hacks" could leave your system unstable!!!!!!!!!!!!


----------------------------------------------------
-----------------Questions / answers----------------
----------------------------------------------------

- Does it works without internet ? / I got errors during download, what can i do ?
It works without internet, you just need to put necessary wad files to the root of the SD card, or of a USB device in FAT32.
Follow this (french) tutoriel to get those files : http://www.wii-info.fr/article-53-comment-recuperer-un-ios-mios-chaine.htm
The necessary IOS are those, in their specific versions :
9 v1034, 12 v526, 13 v1032, 14 v1032, 15 v1032, 17 v1032, 21 v1039, 22 v1294, 28 v1807, 30 v2576, 31 v3608, 33 v3608, 34 v3608, 35 v3608, 36 v3608, 37 v5663, 38 v4124, 50 v4889, 53 v5663, 55 v5663, 56 v5662, 57 v5919, 58 v6175, 60 v6174, 61 v5661, 70 v6687 and 80 v6944.
And thoses "stub" IOSes, within their specific versions : IOS4v65280, IOS10v768, IOS11v10, IOS16v512, IOS20v12, IOS41v3607, IOS43v3607, IOS45v3607, IOS46v3607, IOS48v4124, IOS51v4633 and IOS254v260.
IOs must be named this way : IOSX-64-vY.wad, where X and Y are respectively the version and revision number.

To update the System Menu, you need the file RVL-WiiSystemmenu-vX.wad, where X is 448 for 4.1J, 449 for 4.1U, 450 for 4.1E and 454 for 4.1K.
For Wii Shop, you need RVL-Shopping-v20.wad
For bc, RVL-bc-v6.wad
For MIOS, RVL-mios-v10.wad
For other channels, XY-NUS-vZ.wad, where X is the "type", Y the number and Z the version. By example for Mii Channel it's 1000248414341-NUS-v6.wad (or RVL-NigaoeNR-v6.wad).

For the cIOS installation:
- cIOS 249 : IOS 56 rev 5661
- cIOS 250 : IOS 57 rev 5918
- cIOS 202 : IOS 60 rev 6174
- cIOS 222 : IOS 38 rev 3867
- cIOS 223 : IOS 37 rev 3869
- cIOS 224 : IOS 57 rev 5661

- I got the preloader, will it work ?
If you are not in 4.1 and if you accept the installation of this system menu, you will need to reinstall the preloader and the specifics hacks to this version. Follow this (french) tutoriel to install and configure preloader : http://www.wii-info.fr/article-52-installer-et-configurer-le-preloader.htm

- I have the preloader and i got "system files are corrupted", what can I do ?
If you have the preloader, you must patch "ES_Identify" on the IOS used by this. For Wii 4.x, it's IOS60, else it's IOS 30. Leave the parameters by default if you don't know what you do.

- I have a custom theme, will it stay ?
If you change your Wii version, you will lose all themes and you will need to reinstall a compatible theme with the version of System Menu you have.

- I have cIOSCorp or equivalent installed (to read backup games from disc channel), what will happened ?
If you install IOSes, it will replace those installed by cIOSCorp and you will loose the ability to launch games via disc channel without modchip. But cIOSCorp isn't recommanded, you just need a loader like Neogamma to read backups. If you reinstall cIOSCorp, you will get your old IOS back then Pimp My Wii will tell you that they are outdated

- Should I upgrade my console to 4.1 ? I thougt I must stay to 3.2 ?
If you use this program to put your console to 4.1, you will have exactly the same advantages as a 3.2 Wii, but you will have the improvements of 4.1. You won't have any disadvantages to put your Wii to 4.1.

- Should I install all IOS asked ?
It is recommanded to install IOS indicated as "not present" and IOS 30, 34, 36 and 60. You should also leave parameters by default. If you install at least those, you will avoid most of problems.

- The other IOS, are they useless ?
For other IOS, patching them help launching Trucha Signed gamed on Wii with a modchip.

- I got a message saying that my Custom IOS is outdated, what can I do ?
Follow this (french) tutoriel to upgrade your cIOS : http://www.wii-info.fr/article-40-installer-ou-desinstaller-un-custom-ios.htm