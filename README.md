# UCCNC - Screenset 2046
Screenset for UCCNC https://cncdrive.com/UCCNC.html specifically for the Stepcraft https://www.stepcraft.us/ machines like M500, M700, M1000. The screenset might actually work for you well on other machines too.

![v.0.2](Sceenshot.png)

## Why
Because the native screenset sucks (https://shop.stepcraft-systems.com/uccnc-control-software-oem-package). The default Screenset just does not follow any UI standarts other than that buttons looks like old school buttons, it is not optimized for touch screens whatsoever most importantly the layout and UI is so clumsy that forces us to stop and think, while we should act already.
Don't take me wrong the UCCNC program it self is a solid program that does its work well, but it must be comfortably controlable too or the bits will break or my brain explodes.

The Stepcraft_2046 screenset is equal in fuction to what the Stepcraft_M700 in my case is, but redesigned in a way that is more responsive on touch screens, way more readable, uses common UX logic and in general looks and feels like a contemporary UI.
Sure not all parts of the program are redesigned, only those that we come in touch the most. Specificaly RUN, TOOLPATH and JOG screen.
All the rest stays the same though some icons might be replaced by the new set here and there too.
The screen looks best on something that has 16:9 resolution, at least 1300px wide or more. 

## Status
Testing

## Instalation
The package follows the default UCCNC folder paths. Unpack the files to coresponding folders.

C:\UCCNC\Flashscreens\BMP\Stepcraft_2046
C:\UCCNC\Profiles\Stepcraft_2046.pro
C:\UCCNC\Profiles\Macro_Stepcraft_2046
C:\UCCNC\Screens\Stepcraft_2046.ssf

The macros are the default macros that comes with the Stepcraft M_700 Screenset. No change there.

The Screenset uses Calibri font along the default Arial. If you are on old Windblows you can download the font for free from https://dl.freefontsfamily.com/download/Calibri-Font/ 

## Try and run
Run the UCCNC program, go to Configuration > Profiles. Select "Stepcraft_2046" profile, click "load profile". The program will quit and restart with the Stepcraft_2046 profile ready to be used & tested.

## Testing
Although the profile has been tested and looks good, you never know. Be carefull and let me know if there is anything that should be fixed, be it wrong event mappings or design flaws. Fire up github issue and be as desriptive as you can, ideally include screenshots with description.

## If you like it so much
You can make the profile as your default by rewriting your UCCNC shortcut to something like - open short cut properties and set target to:
C:\UCCNC\UCCNC.exe /p Stepcraft_2046
which basically says run UCCNC with the profile "Stepcraft_2046", that is it.

## Tweak it
Sure, you can add your own buttons, and tweak it to your liking. The "Edit screen" button is in General settings.
Here is how https://youtu.be/_5kHN4LvtGU 

## What if want I the whole program UI be optimized
Well, it takes awefull lot of hours of work which needs to be covered somehow.
Think about it.  

## Moo info
https://www.forum.cncdrive.com/viewtopic.php?f=9&t=3731