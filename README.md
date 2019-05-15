## A simple rEFInd theme

[rEFInd](http://www.rodsbooks.com/refind/) is a boot manager for UEFI-based systems. This is a simple theme for it.

![Screenshot](https://i.imgur.com/7NZgxoE.png)

### Usage

 1. Make sure you have installed rEFInd. 
 2. Go to rEFInd's folder in ESP, which is often `/boot/efi/EFI/refind` or similar.
 3. Create a folder called `themes` and clone this repository inside that folder.
 4. To enable this theme add `include themes/evil/theme.conf` at the end of `refind.conf`.

### Credits

 - Part of the images are taken from [EvanPurkhiser/rEFInd-minimal](https://github.com/EvanPurkhiser/rEFInd-minimal)
