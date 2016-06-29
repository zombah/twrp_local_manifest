# Local manifest to build TWRP Android 6.0 recovery #

## How to download: ##

Initialize repo:

>repo init -u git://github.com/lj50036/platform_manifest_twrp_omni.git -b twrp-6.0  
>curl --create-dirs -L -o .repo/local_manifests/pop35.xml -O -L https://raw.githubusercontent.com/zombah/twrp_local_manifest/twrp-6.0/pop35.xml  
>repo sync  


## How to compile: ##

>source ./build/envsetup.sh  
>lunch omni_pop35-userdebug  
>make recoveryimage  
