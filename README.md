---------------------------------------------------------------------------------------
 Getting Started:
 ==============

To get started with FusionOS, you'll need to get familiar with [Repo](https://source.android.com/source/using-repo.html) and Version Control with [Git](https://source.android.com/source/version-control.html).

To initialize your local repository, use a command like this:

```bash
repo init -u https://github.com/FusionOS-org/android_manifest.git -b eleven

```

Then to sync up:

```
repo sync -c -f --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j8
```

---------------------------------------------------------------------------------------
 Compilation of FusionOS:
 ==================

From root directory of Project, perform following commands in terminal

```bash
$ . build/envsetup.sh
$ lunch fuse_$device-userdebug
$ brunch <device_codename>
```
---------------------------------------------------------------------------------------
 Credits:
 =======

 * [**LineageOS**](https://github.com/LineageOS)
 * [**RevengeOS**](https://github.com/RevengeOS)
 * [**POSP**](https://github.com/PotatoProject)
 * [**AOSiP**](https://github.com/AOSiP)
 * [**DotOS**](https://github.com/DotOS)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**Havoc-OS**](https://github.com/Havoc-OS)
 * [**Xtended**](https://github.com/Project-Xtended)
 * [**OctaviOS**](https://github.com/Octavi-OS)
 * [**ColtOS**](https://github.com/Colt-Enigma)
