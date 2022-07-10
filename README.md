# LSPosed Framework

## Introduction 

A Riru / Zygisk module trying to provide an ART hooking framework which delivers consistent APIs with the OG Xposed, leveraging LSPlant hooking framework.

> Xposed is a framework for modules that can change the behavior of the system and apps without touching any APKs. That's great because it means that modules can work for different versions and even ROMs without any changes (as long as the original code was not changed too much). It's also easy to undo. As all changes are done in the memory, you just need to deactivate the module and reboot to get your original system back. There are many other advantages, but here is just one more: multiple modules can do changes to the same part of the system or app. With modified APKs, you have to choose one. No way to combine them, unless the author builds multiple APKs with different combinations.

## Supported Versions

Android 8.1 ~ 13 Beta 1

## Install

1. Install Magisk v23+ (Riru) / v24+ (Zygisk)
2. (For Riru flavor) Install [Riru](https://github.com/RikkaApps/Riru/releases) v25+ from Magisk repo
3. [Download](#download) and install LSPosed in Magisk app
4. Reboot
5. Follow the prompt to add LSPosed shortcut to launcher
    - Some launchers won't show a prompt but silently add the shortcut
    - If the shortcut cannot be added, you can install the manager located at `/data/adb/lspd/manager.apk` manually
    - If you accidentally deleted the shortcut, reboot your device or install the manager manually to add the shortcut again
    - If you don't need a shortcut, install the manager manually and you can disable future shortcut being added in the settings
    - In any case, you can dial `*#*#5776733#*#*` (aka LSPosed) to launch the manager if you have a dialer
6. Have fun :)

## Download

For stable releases, please go to [Github Releases page]()
For canary build, please check [Github Actions]()
Note: debug builds are only available in Github Actions.

## Get Help

## For Developers

Developers are welcome to write Xposed modules with hooks based on LSPosed Framework. A module based on LSPosed framework is fully compatible with the original Xposed Framework, and vice versa, a Xposed Framework-based module will work well with LSPosed framework too.

- [Xposed Framework API](https://api.xposed.info/)

## Community Discussion

Notice: These community groups don't accept any bug report, please use [Get help](#get-help) to report.

## Translation Contributing

## License

LSPosed is licensed under the **GNU General Public License v3 (GPL-3)** (http://www.gnu.org/copyleft/gpl.html).
