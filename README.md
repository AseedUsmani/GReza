# GReza
A GRUB theme customization App.

Tips on customization:
1) The script will ask for an image path, it can be an internet URL or a local path.
2) The color of the custom message you enter is in RGB, where `#FFFFFF` is white and `#000000` is black. Enter a blank message to remove the image.
3) The bootloader images (background and selected) are determined by `select_bkg_\*.png` and `select_bg_\*.png`; where c stands for center, n, ne, s etc stands for North, North-East, South etc. Same rule applies to terminal background.
4) You can edit theme.txt for further customization.
5) To change the order or the names of the menu items in bootloader, edit `/boot/grub/grub.cfg`.
6) In case an icon is missing, add `--class <icon_name>` to the line containing the menu item. For example:
`submenu 'Advanced menu for Ubuntu' --class submenu`... will put the image file `submenu` as the icon of this item.
