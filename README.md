# JavaBinder
Jupyter Notebooks of Java Practice

The amazing combination of Jupyter with Java.

The only real issue is keeping track of scope and garbage collection in terms of variables staying from deleted cells.

Todo:
Figure out Binder to allow truely interactive notes. 
https://mybinder.org/

Thank you to https://github.com/SpencerPark/IJava and https://github.com/jupyter/notebook and https://github.com/ContinuumIO

My personal setup is:

Thinkpad w520:
  - windows 8.1 pro with mc
  - my notebooks live in a Dropbox folder that's synced with this repo for redundancy
  - the base install is anaconda, which includes jupyter along with numpy, matplotlib, etc; with a modified working directory
  - the IJava kernel was installed, which requires JDK 9+
  
Samsung Chromebook Pro:  https://github.com/dnschneid/crouton
  - xubuntu installed in a chroot after enabling developermode and crouton
  - python3, jupyter, openjdk, etc installed; IJava kernel installed
  - start by using enter-chroot ; jupyter notebook --port 9999 (chromeos can get fussy about ports)
  - *no automatic file sync with cloud (no dropbox support with live file uploading), either use android app foldersync, or do it manually
  - ** automatic file sync is possible if xfce4 is started (I prefer not to use xiwi because it lacks hw gpu accel)
