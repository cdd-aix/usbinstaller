# USB Installer

Shell script to create bootable Ubuntu USB that:
* Works on BIOS and EFI
* Works on PCs that have serial console and no video
* Trivial to edit after creation

## Usage
* Insert USB stick into running Linux host with this software
* Run 'sudo usbinstaller $usbBlockDevice [$flavor]' at Linux command prompt
* Insert USB into PC, power on see Linux boot
* Edit kernel command line with console=ttyS0,115200n8 if using ubuntu server instead of ubuntu live server

## Notes
* In theory ubuntu desktop and server installs can be unattended

## To Do
* Open ticket "Subiquity should search kernel command line for answerfile location."

