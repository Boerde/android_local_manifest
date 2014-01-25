Repositories that are needed to build CyanogenMod 11 for Galaxy Mini 2

Steps to build cyanogenmod for Galaxy Mini 2:
1. If you get stuck/ dont know how to setup read: http://wiki.cyanogenmod.org/w/Build_for_hero 

2. repo init -u git://github.com/CyanogenMod/android.git -b cm-11.0

3. cd .repo

4. git clone https://github.com/Boerde/android_local_manifest.git -b cm-11.0 local_manifests

5. cd ..

6. repo sync

7. wait

8. Apply Patches 
	
	- cd device/samsung/msm7x27a-common/patches
	
	- ./install.sh
	
8. source build/envsetup.sh

9. lunch cm_jena-userdebug

10. croot

11. brunch jena
