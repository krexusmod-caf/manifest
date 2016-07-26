<p align="center">
  <img src="https://raw.github.com/krexus-caf/manifest/caf/krexus-caf-logo.png" width="600">
</p>


*Stock nexus on your Qualcomm device, "as it should be"*
------------------------------

Manifest
========

**CodeAURORA 6.0.x** (latest is LA.BR.1.2.7_rb1.20)

1. Initialize the marshmallow repo's **OMS branch**			
`repo init -u https://github.com/krexusmod-caf/manifest.git -b caf-oms`

2. Sync		
`repo sync -c -f -j8 --force-sync --no-clone-bundle --no-tags`

3. Load the environment		
`ln -s vendor/krexus/utils/krebuild.sh krebuild.sh`		
`. krebuild.sh`

4. lunch & download device repos	
`lunch ******`

5. Build!
`mka otapackage`

CAF Credits
------------
This CAF Krexus source was made possible by [AOSP-CAF](https://github.com/AOSP-CAF)		
and the work of [Meninblack007](https://github.com/Meninblack007)		

Krexus Credits
------------
Huge thanks to:  
[George G.](https://github.com/KreAch3R)		
[Ezio Lacandia Bijelkic](https://github.com/ezio84)		
[Dario Ferretti](https://github.com/AndroidRul3z)		
[CallMeAldy](https://github.com/CallMeAldy)		
[Sykopompos](https://github.com/Sykopompos)		
[rascarlo](https://plus.google.com/+CarloDiNuccio/)		
[BeansTown106](https://github.com/BeansTown106)		
[SlimRoms](https://github.com/SlimRoms)		
[Cyanogenmod](https://github.com/CyanogenMod)  
Google	
AOSP  
CodeAURORA
