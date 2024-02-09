# Proton-X50-ATLAS-Carplay-FromX90
# A script to install CarPlay apps in Proton X50 IHU taken from Proton X90

If you updated to ATLAS version 617 / 618 from 2-Mar-2023 onwards, most probably this won't works for you.

If you updated to ATLAS version 617 / 618 from 2-Mar-2023 onwards and really wanted to install apps in IHU, you can [flash ATLAS version 617v1 / 618v1 with following guide](https://github.com/xeon1989/Proton-X50-IHU-Upgrade-Downgrade/blob/main/README.md). <br><br>

If you want to avoid applying changes on IHU, you may use this [Modded QDLink](https://github.com/xeon1989/QDLink-Unlocked) for less restricted experience. <br><br>

# Before you start
- This guide meant for advance user.
- You need to downgrade to ATLAS version 617 beforehand, then you can just install Autokit with this script. 
- Strictly follow the steps. In case you break your IHU (although almost impossible if you adhere to the guide), I can't fix for you. :)


# What it does
- This script will install Carplay that has been taken from Proton X90 development. 
- Script also disables OTA functionality and QDLink. 

## Prepare your Carlinkit 3.0 Wireless Carplay Adapter (Choose Wireless Version)
Buy dongle from shoppee.
- https://shp.ee/jyuqs16


# Prepare your files
- Need to use pendrive 32Gb and below only. Make sure formatted to Fat32. 
- (https://drive.google.com/file/d/1dXEw2lHZk25Mo5FT_lB2Bllhku1L7Mgi/view?usp=sharing)
<br><br>


# Installation
1. Now you have prepared your USB! Extract and place content inside "install" folder into USB.
2. Eject USB from PC, plug it in IHU’s USB port. 
5.  When the script start executing, IHU shows “Wireless Charging” screen. Wait patiently for around 5 min. 
6.  Once script ended, IHU shows Settings app and restart IHU.
7.  IHU optimizing apps after restart. This might take up to 15-20min. Make sure you do not turn off IHU.  
8.  After IHU started, apps should be installed.
9.  Connect Carlinkit to use with Carplay app. Tutorial can be found here. https://t.me/PROTONX50IHU

# Uninstall autokit app

1. Delete or move files in your USB drive, then copy content of /Custom App/uninstall/ to USB drive.
2. Plug it in IHU and wait for reboot. 


## Known Issue
1. Steering wheel button are not working. See [this docs](SteeringButtonWorkaroundAA.md) for the workaround.
2. No icon will show after the installation. The application will show after you reboot @ fresh start your car. Or just plug your dongle to open the app.
