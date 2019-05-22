# LEGAL NOTICE
You assume all responsibilty for using these files and become liable for any damages that may result by doing so. These files are provided AS-IS and are not provided under any warranty implied or express. These files are Copyright &copy; Lenovo. Any attempt to dissasemble, modify, or reverse engineer them may result in legal issues with Lenovo. I am merely providing them, unaltered and in their original state, so that as a last resort, you may recover your bricked laptop using a serial programmer or BIOS flasher. 


## BIOS
Contains BIOS files for the 720s-13ARR. These files were extracted from the fd files found in Lenovos original installers for the BIOS updates. 


Please make sure you verify these files before installing them, the checksums (MD5) are listed here:


### BIOS Checksums
Note that these were generated using the program md5sum.


```
acb4d71ccd0e75ffaeaf78d782c0d60e  V28.bin
8027a4f51a8aaeee968428a000db36ec  V29.bin
e1d60d7721d6effe59b89b29e970ae4c  V30.bin
79b215cfe4fc65397eeb628be67140cd  V37.bin
f257d0a0d907a97433cb126c93b73da7  V38.bin
404e6d4eaa31af66e306ea48f8d0ae7f  V40.bin
001b4a4b6bbebbb05aa10c8e282f153d  V41.bin
```


## WARNING
These are raw BIOS regions extracted from Lenovos official fd files for the BIOS updates. Flashing any of these files in their current state will give you a working laptop however, they will also overwrite the SLIC table found inside your current BIOS. You will lose all identifying information pertaining to your laptop that is normally embedded in your BIOS including the Serial Number and Windows 10 Pro OEM key.


You must first extract your current BIOS and merge in your SLIC table to preserve the uniqueness of your laptop. Normally, this is done by Insydes flashing software but if you are here, then your computer is already bricked and you cannot use Insydes software. If you are uninterested in manually doing this or lack the abilities to do so, then please be aware of the consequences. The Windows 10 Pro OEM key is non-recoverable. Once it is flashed over, it is gone forever, as it is tied to your motherboard.


I cannot perform this for you, as I lack the skills to do so myself.


**WARNING** Do not install V30 or below if you are on V37+, there is no reason to do so and they will likely brick your machine.


##UPDATES
UPDATE May 22nd, 2019: I have updated the repository to include the readme text for each release. I have also uploaded the most recent raw BIOS images from Lenovo up through December 2018. 
