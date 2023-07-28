## This file has been archived, please go back to [Readme](../README.md)

1. It is essentially changing the appearance using the Vivaldi browser’s custom UI MOD feature
2. If you want to return to the original effect, you just need to delete the local CSS
3. This configuration also works on Windows. In the process of setting the shortcut keys, simply replace `Command` with `Ctrl`

### 1. Install Vivaldi Browser

- Install a [Vivaldi](https://vivaldi.com) browser first, no doubt.

### 2. Open Vivaldi Settings

> During the setup process, you can search for keywords in the upper left corner of the "Settings" page to quickly locate
- **Appearance** > Status Bar > `Status Info Overlay`
- **Tabs** > Tab bar position > `Left`
- **Tabs** > Tab Stacking > `According`
- **Panel** > Panel Options > `Check 'Floating Panel'`
- **Address Bar** > `Uncheck 'Show Address Bar'`
- **Quick Commands** > `Check 'Open Links In New Tab'`
- **Keyboard** (Set the necessary keyboard shortcuts)
    - New Tab > Remove it
    - Quick Command > `Command + T`
    - Save Page As > Remove it
    - Tab Bar > `Command + S`
    - Address Bar > `Command + B` (Remove Booksmarks shortcuts first in Windows)
    - Create Bookmark > Remove it
    - Pin / Unpin Tab > `Command + D`
    - Print > Remove it
    - Panel > `Comand + P`

### 3. Custom UI Mod

- [Download the mod](https://github.com/tovifun/VivalArc/archive/refs/heads/main.zip), extract it to anywhere safe on your PC
- **Themes > Open Theme** >  ArcLight.zip
- Open `vivaldi://experiments` and enable `"Allow for using CSS modifications"`
- Open Settings > Appearance > Custom UI MOD
- Select the folder where you've extracted it
- Restart Vivaldi