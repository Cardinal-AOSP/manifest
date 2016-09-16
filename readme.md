<img src="https://raw.githubusercontent.com/Cardinal-AOSP/manifest/n7/crd.png">
=============

To initialize your local repository using the Cardinal-AOSP trees, use a command like this:

To sync Cardinal-AOSP
````bash
repo init -u git://github.com/Cardinal-AOSP/manifest.git -b n7
```
Then to sync up:
````bash
repo sync
```
Finally to build:
````bash
./wings.sh device_codename
```
Example:
````bash
./wings.sh kenzo
```
Make Commands:
````bash
mka InitiateWings, mka cardinal, mka otapackage
```
