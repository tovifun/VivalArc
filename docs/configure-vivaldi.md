1. It is essentially changing the appearance using the Vivaldi browser’s custom UI MOD feature
2. This configuration also works on Windows. In the process of setting the shortcut keys, simply replace `Command` with `Ctrl`
3. If you want to return to the original effect, you just need to delete the local CSS

---

## 🛠️ Configuration Steps：

### 1. Install Vivaldi Browser

- Install a [Vivaldi](https://vivaldi.com) browser first, no doubt.

### 2. Open Vivaldi Settings

> During the setup process, you can search for keywords in the upper left corner of the "Settings" page to quickly locate

**Must-haves** 
- **Tabs** > Tab bar position > `Left`
- **Panel** > Panel Options > `Check 'Floating Panel'`
- **Address Bar** > `Uncheck 'Show Address Bar'`
- **Quick Commands** > `Check 'Open Links In New Tab'`
- **Keyboard** (Set the necessary keyboard shortcuts)
    - New Tab > Remove it
    - Quick Command > `Command + T`
    - Save Page As > Remove it
    - Tab Bar > `Command + S`
    - Address Bar > `Command + B` (Remove Booksmarks shortcuts first in Windows)
- **Additional Scrollbar Configuration for Windows Users**: As the default Windows scrollbar is quite prominent and somewhat unattractive, we require an extra tweak to optimize its appearance. Here's how to do it:
  - Enter this in the address bar: `chrome://flags``
  - Search for `windows fluent scrollbars` and enable it，than you'll have a more subtle scrollbar.

**Nice-to-haves**
- **Appearance** > Status Bar > `Status Info Overlay`
- **Tabs** > Tab Stacking > `According`
- **Keyboard** (Set the necessary keyboard shortcuts)
### 3. Custom UI Mod
    - Create Bookmark > Remove it
    - Pin / Unpin Tab > `Command + D`
    - Print > Remove it
    - Panel > `Comand + P`

- [Download the mod](https://github.com/tovifun/VivalArc/archive/refs/heads/main.zip), extract it to anywhere safe on your PC
- **Themes > Open Theme** >  ArcLight.zip
- Open `vivaldi://experiments` and enable `"Allow for using CSS modifications"`
- Open Settings > Appearance > Custom UI MOD
- Select the folder where you've extracted it
- Restart Vivaldi