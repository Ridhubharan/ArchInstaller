# ArchInstaller
A script to automatically install Arch Linux. We all love Arch Linux but it is time consuming to install it manually.<br>
So this script will automate the installation process.

## Download Arch ISO
Download the latest ISO from https://www.archlinux.org/download/

## Make bootable drive
Download Etcher from https://www.balena.io/etcher/ and flash your pendrive with Arch Linux

## Using the script
Boot into Arch live and make sure your are connected to internet.<br>
Then run the following command.

     wget ridhu.tk/arch/installer1.sh
     chmod +x installer1.sh
     ./installer1.sh
     
After successful completion of the script, you will get an instruction to download "installer2.sh"<br>
Run the following command.

     pacman -S wget sudo vim
     wget ridhu.tk/arch/installer2.sh
     chmod +x installer2.sh
     ./installer2.sh
     
When you run the second script you will be asked to enter some information. Enter those details.<br>
Once the installer2.sh is finished, the system will restart and you will be greeted with SSDM login manager.<br>
Login using the details that your provided in installer2.sh.<br>
When you click login, KDE Plasma will be launched by default
