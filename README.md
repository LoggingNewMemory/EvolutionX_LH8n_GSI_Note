![EvoX GSI Banner](https://github.com/user-attachments/assets/f7a92be6-fc95-4732-8a42-a9bf61e79dbb)

# Evolution X GSI Note
## A Note By: Kanagawa Yamada

Instruction: [HERE](https://t.me/KanagawaLabAnnouncement/91) <br />
Note Version: 3.0 <br />
Download: [HERE](https://github.com/mytja/treble_evo/releases) (Use normal (not slim) ver) <br />

- GApps included, all you have to do is extract the .img.xz
- Non root
- ~~Integrity can be upgarded to strong integrity~~ (Actually I doubt it still work)

Req Module:
- [Brightness Fix](https://t.me/KanagawaLabAnnouncement/83)
- [Original Camera](https://t.me/KanagawaLabAnnouncement/80)
- [100% Battery Autocut](https://github.com/LoggingNewMemory/Autocut-Charging-MYTH)

What work:
- Wifi
- Location
- Speaker
- SMS
- Bank App (in this case blu BCA)
- Whatsapp without spoofing
- Camera (Even the stock)
- High Refresh Rate (120 Hz)
- Fast charging (Up to 20 Watt)
- DTS audio can be toggled on audio effects (Pph Treble settings)
- Integrity is device meet by default
- Safetynet Passed
- Built in Game Space

How to upgrade to strong integrity (Thanks to : Blank's Integrity Guide)

Note: Make sure you use [Magisk Alpha](https://github.com/CoderTyn/Magisk-Alpha) or [KernelSU](https://github.com/tiann/KernelSU) <br />
KERNELSU IS RECOMMENDED 

1. disable "Play Integrity Fix" on setting, and then reboot
2. Delete /data/adb/tricky_store/ if exist
3. Completely remove all your root solution module (Eq: Bootloader Spoofer or something else)
4. Install:
   - [Zygisk Next](https://github.com/Dr-TSNG/ZygiskNext/releases)
   - [Shamiko](https://github.com/LSPosed/LSPosed.github.io/releases)
   - [Sensitive Props](https://github.com/Magisk-Modules-Alt-Repo/sensitive_props/releases)
   - [LSPosed Mod](https://github.com/mywalkb/LSPosed_mod/releases)
   - [Tricky Store](https://github.com/5ec1cff/TrickyStore/releases)
   - [Play Integrity Fix](https://github.com/chiteroman/PlayIntegrityFix/releases)
6. Reboot
7. Open LSPosed Manager
8. Enable "Disable Verbose Logs"
9. Disable "Enable Watchdog Logs"
10. Install HMA (Provided on Release Page)
11. Import HMA Config

How to hide root?

Magisk Alpha: Add apps to magisk denylist (DO NOT SELECT PLAY STORE, GOOGLE SERVICE FRAMEWORK, AND GOOGLE PLAY SERVICE)
KernelSU: 
1. Go to "App Manage"
2. Search the app you want to hide
3. Toggle Enable Hide
4. Press "Using 0 Templates" (Under Template Config) and select Hidden
5. Press back arrow to save it

Known Issue
- Quick Share crashes the entire system
- Sometimes, if you go to pph terble settings -> misc features the system crashed and send you to fastboot. Just hold power button and reboot, you will be fine
- WZM Crashed
- There is no way to bring backlight effect here
- Even thou NFC is available, but it seems not working
