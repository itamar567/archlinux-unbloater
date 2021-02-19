# What Is Unbloater?
Unbloater is a quick script i wrote in bash to remove unnecessarily packages from my ArchLinux system.
# How can I use it?
1. clone this repository and install the package:  
`git clone https://github.com/itamar567/archlinux-unbloater.git && cd archlinux-unbloater && makepkg -si`

2. run the script:
`unbloater`
3. you will notice a dialog telling you to select the packages you want to keep. make sure to select only the packages you installed and want to keep.  
don't worry about dependencies as you will run `pacman -Run`, which will not remove packages if they are a dependency of another package.  
**MAKE SURE TO SELECT `base`,`linux`, AND YOUR BOOTLOADER, AS YOUR SYSTEM MIGHT NOT BOOT**
4. after you selected all the packages you want to keep, press `enter` and run `pacman -Run $(cat bloated_packages)`. This will uninstall all unneeded packages.
5. reboot.  
  
Note: you might need to install some packages that you forgot to select.
