## A simple rEFInd theme

[rEFInd](http://www.rodsbooks.com/refind/) is a boot manager for UEFI-based systems. This is a simple theme for it.

![Screenshot](https://i.imgur.com/RFN5k8A.png)

### Usage

 1. Make sure you have installed rEFInd. 
 2. Go to rEFInd's folder in your [EFI System Partition](https://en.wikipedia.org/wiki/EFI_system_partition).
 3. Create a folder called `themes` and clone this repository inside that folder.
 4. To enable this theme add `include themes/evil/theme.conf` at the end of `refind.conf`.
 5. This theme works best at 1920x1080. You may need to edit it if you use a different resolution.

### Attribution

 - Some icons are taken from [EvanPurkhiser/rEFInd-minimal](https://github.com/EvanPurkhiser/rEFInd-minimal).
