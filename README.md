![EvoX GSI Banner](https://github.com/user-attachments/assets/f7a92be6-fc95-4732-8a42-a9bf61e79dbb)

# Evolution X GSI Note
## A Note By: Kanagawa Yamada

Instruction: [HERE] (https://t.me/KanagawaLabAnnouncement/91)
Note Version: 3.0
Download:[HERE] (https://github.com/mytja/treble_evo/releases) (Use Pre-Release normal (not slim) ver)

- GApps included, all you have to do is extract the .img.xz
- Non root
- Integrity can be upgarded to strong integrity

Req Module:
- [Shamiko] (https://github.com/LSPosed/LSPosed.github.io/releases)
- [Zygisk Next] (https://github.com/Dr-TSNG/ZygiskNext)
- [Brightness Fix] (https://t.me/KanagawaLabAnnouncement/83)
- [LSPosed Mod] (https://github.com/mywalkb/LSPosed_mod/releases) (Download the Zygisk Ver)
- [Original Camera] (https://t.me/KanagawaLabAnnouncement/80)
- [100% Battery Autocut] (https://t.me/KanagawaLabAnnouncement/74)

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

Note: Make sure you use (Magisk Alpha) [https://github.com/CoderTyn/Magisk-Alpha] or (KernelSU) [https://github.com/tiann/KernelSU] <br />
KERNELSU IS RECOMMENDED 

1. Delete /data/adb/tricky_store/ if exist
2. Completely remove all your root solution module (Eq: Bootloader Spoofer or something else)
3. Install Zygisk Next, Shamiko, Sensitive Props, LSPosed Mod, Tricky Store, Play Integrity Fix
4. Reboot
5. Open LSPosed Manager
6. Enable "Disable Verbose Logs"
7. Disable "Enable Watchdog Logs"
8. Install HMA
9. Import HMA Config

How to hide root?

Magisk Alpha: Add apps to magisk denylist (DO NOT SELECT PLAY STORE, GOOGLE SERVICE FRAMEWORK, AND GOOGLE PLAY SERVICE)
KernelSU: 
1. Go to "App Manage"
2. Search the app you want to hide
3. Toggle Enable Hide
4. Press "Using 0 Templates" (Under Template Config) and select Hidden
5. Press back arrow to save it

Known Issue
- ~~Quick Share crashes the entire system~~ (Fixed by upgrading the integrity to strong)
- Sometimes, if you go to pph terble settings -> misc features the system crashed and send you to fastboot. Just hold power button and reboot, you will be fine
- WZM Crashed
- There is no way to bring backlight effect here
