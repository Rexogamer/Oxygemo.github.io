### Trackpad


# Table of Pages
[Index](../) | [Acer trackpad trick for Linux](acertrick.md) | [Low-end PC Tweaks](/tweaksandmore/lowendtweaks.md) | [Donate](/personal/donate.md)
# Enable Acer trackpad support for GNU/Linux
**If you have a laptop from Acer running GNU/Linux, you've probably encountered this.**

"My trackpad isn't working no matter what I do!"

**To answer that, it's something Acer has enabled by default in their UEFI bios. If you disable it, your trackpad will work.**

Do the following:
  
  1. Boot your machine into the Setup Utility (usually F2 is the button that does this)
  2. Navigate to Main
  3. Find "Trackpad"
  4. Change it from Advanced to Basic (Advanced requires a I2C driver of some sorts, I assume that's the Win10 driver, and that wont work on anything that isn't Windows 10.)
  5. Reboot to your GNU/Linux distro of choice and enjoy your trackpad.
  
