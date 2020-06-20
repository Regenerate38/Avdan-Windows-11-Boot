# Avdan-Windows-11-Boot
Plymouth theme based on Youtuber Avdan's Windows 11 Concept Boot.

Use the command below to add plymouth theme tool. 
sudo apt install plymouth-themes

Set the new theme using:

sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/path/to-your-plymouth.plymouth 100

Then run the command below.

sudo update-alternatives --config default.plymouth

sudo update-initramfs -u
