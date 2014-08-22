Recovery-philz patched for x86
===============================
by qubex, thanks to Hazou and moonbutt for the patches
===============================

__<center><big>Recovery-philz patched for x86 </big></center>__

.


#### Building

If you regularly build ROMs/Recoveries for your device, and have a working CWM setup
on your build machine, then you can quickly set up and build Philz Touch recovery as well


Clone philz recovery to bootable/recovery-philz folder

    git clone https://github.com/lenovo-k900/android_bootable_recovery-philz bootable/recovery-philz

Now build with RECOVERY_VARIANT flag set to philz.

    . build/envsetup.sh && lunch && make -j8 recoveryimage RECOVERY_VARIANT=philz

or

    export RECOVERY_VARIANT=philz
    . build/envsetup.sh && lunch && make -j8 recoveryimage
