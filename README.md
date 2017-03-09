<img src="https://raw.githubusercontent.com/Cardinal-AOSP/manifest/n7/crd.png">

Cardinal-AOSP
===================


Getting Started
---------------

To get started with Cardinal-AOSP, you'll need to get familiar with
[Git and Repo](http://source.android.com/download/using-repo).


To initialize your local repository, use this command:


	repo init -u git://github.com/Cardinal-AOSP/manifest.git -b n-mr2 -m crd.xml



Time to sync source! [I love this part]:

	repo sync -c -f -j8 --force-sync --no-clone-bundle --no-tags

Compiling the source!
---------------------
	. build/envsetup.sh
	lunch cardinal_$device-userdebug
	mka bacon -j#
