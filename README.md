NamelessRom
=========================

Work in Progress!

To get started

repo init -u https://github.com/NamelessRom/android.git -b n-2.1

Requirements
-------

You need to have gradle installed. Please have a look at the [Installation Guide](https://docs.gradle.org/current/userguide/installation.html) or at our gradle [Installation Script](https://github.com/NamelessRom/android_vendor_nameless/blob/n-2.1/tools/installation/install-gradle.sh), which automatically installs gradle for you.


You will also need to install the android sdk and set it up. To do this, download the [Android SDK]() and extract it, to let's say, ```/opt/android/sdk```.

After downloading and extracting, open up your terminal, go to /opt/android/sdk/tools and issue ```./android list sdk --all```. It will list available packages to install.

You will need the following:

  * Android SDK Tools, revision 24.3
  * Android SDK Build-tools, revision 22
  * Android SDK Platform-tools, revision 22.0.1
  * SDK Platform Android 5.1.1, API 22, revision 2
  * Android Support Repository, revision 15
  * Android Support Library, revision 22.2
  * Google Play services, revision 25
  * Google Repository, revision 19
  * Google Play Billing Library, revision 5

You will see those listed with numbers, choose the correct numbers and install them.

Example command for installation

```
./android update sdk -u -a -t 1,2,5,24,139,140,144,145,146,147,148,149
```
