# 2016PilotOneClick

**破解步骤和注意事项已添加到wiki：**
* https://github.com/toddyhan/2016PilotOneClick/wiki



**_2016 Honda Pilot One-Click Root &amp; App Installation Tool_**

Many thanks to purespin on XDA for figuring out the signature check mechanism!

This project is a collection of utilities & scripts to get root access on a 2016 model Honda Pilot head unit, as well as simplifying installation of third party (non-Honda) apps. 

**USE AT YOUR OWN RISK!**

_These scripts do not implement a lot of error checking. While it does present a user with a final double check of important things before comitting changes, these scripts WILL modify your head unit and have the potential to "brick" it. You have been warned._ 

## Usage

OneClickInstall.(bat)(sh) HeadUnitIP My.apk

Important:
Please rename APKs to be installed to remove any spaces or crazy characters. This will not impact the final appearance of the app on the head unit, so keeping it short is preferred. These scripts will fail if this is not accomplished and results may vary. Something like "Waze.apk" is perfect, names like "My crazy APK Is @Wsome! v2.28.apk" will not work. 

These scripts will root the head unit if it's not already. 

## References:

This project uses code or utilities from the below authors:

dirtyCOW exploit: I based a different implementation of the dirtyCOW exploit on the below code:
https://github.com/timwr/CVE-2016-5195

Many thanks to purespin on XDA for figuring out the signature check mechanism!

In an effort to maintain fewer scripts to use on both Windows and Linux platforms, use of win-bash was used, located here:
https://sourceforge.net/projects/win-bash/

The scripts also assume working installations of the Android Software Development Kit and a working Java runtime environment. 

Contributions are welcome and encouraged - keep in mind this is a hobby project for a father of two with a (separate! haha) full-time job, so I may at times be slow to respond. 


