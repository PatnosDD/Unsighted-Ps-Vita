# Unsighted for the PS Vita
This repository contains the necessary patches to create fully functional files for running Unsighted on the PS Vita.

**IMPORTANT:** You must own **Unsighted** on **Steam** or **GOG** to use this patch!  

---
### Known Issues  

- Incorrect Controller Button Glyphs
- Lower FPS in levels with high amount of enemies

**If you want to support the project, you can leave a tip on one of those websites:**

Ko-Fi: https://ko-fi.com/patnosd

Patreon: https://www.patreon.com/PatnosD

PayPal: https://paypal.me/DPatnosD

Afdian: https://afdian.com/a/PatnosD

## PS VITA Set up

In order to have the best possible experience, I recommend you to use following plugins (that you should be able to find somewhere on the net) :
- ioplus.skprx
 **+ Full CPU Overclock (500Mhz)**
↓**OPTIONAL**↓
- iostaging.skprx




## Instructions

### Prerequisites
1. Install the Unsighted `.VPK` using **VitaShell** or download it straight from **VitaDB** on your PS Vita.  
   *Do not attempt to launch the game yet, as it will crash without the required files.*
2. Ensure you have purchased and downloaded the game from **Steam** or **GOG**.
3. Overclocking is necessary to run the game properly.

---

### STEAM VERSION
1. Visit the **Releases** page of this repository and download `UnsightedVitaSTEAM.zip`.
2. Extract the downloaded zip to a folder on your PC.
3. Copy the Steam game folder into the extracted folder.  
   **Note:** Your `UnsightedVitaSTEAM` folder should look like this:
```
   └── UnsightedVitaPatchSteam/
    ├── Unsighted/  <- ../steamapps/common/Unsighted
    ├── vcdiff/
    ├── APPLYPATCH.bat
    ├── deterministic.exe
    └── xdelta3-x.x.x-x86_64.exe
```
4. Run `APPLYPATCH.bat` and wait for the process to complete (this can take 15–25 minutes depending on your system).
5. Once completed, you will see a file named `UnsightedVITA.zip`.
6. Using **VitaShell**, connect your PS Vita to your PC and copy the extracted contents of `UnsightedVITA.zip` (_zip file should be around 380–450MB_) to `ux0:app/UNSI22233/`.
   **Note:** Your `UNSI22233` folder on your Vita should look like this:
```
   └── UNSI22233/
    ├── Media/
    ├── sce_module/
    ├── sce_sys/
    └── eboot.bin
```
7. When prompted, select **Replace the files in destination**.
8. if you encounter any issues take a look at the [Troubleshooting](#troubleshooting) section
9. Launch the game and enjoy!

---

### GOG VERSION
1. Visit the **Releases** page of this repository and download `UnsightedVitaGOG.zip`.
2. Extract the downloaded zip to a folder on your PC.
3. Copy the GOG game folder into the extracted folder.  

   **Note:** Your `UnsightedVitaGOG` folder should look like this:
```
   └── UnsightedVitaPatchSteam/
    ├── Unsighted_Data/  <- ../GOG/Unsighted/Unsighted_Data
    ├── vcdiff/
    ├── APPLYPATCH.bat
    ├── deterministic.exe
    └── xdelta3-x.x.x-x86_64.exe
```
4. Run `APPLYPATCH.bat` and wait for the process to complete (this can take 15–25 minutes depending on your system).
5. Once completed, you will see a file named `UnsightedVITA.zip`.
6. Using **VitaShell**, connect your PS Vita to your PC and copy the extracted contents of `UnsightedVITA.zip` (_zip file should be around 380–450MB_) to `ux0:app/UNSI22233/`.
   **Note:** Your `UNSI22233` folder on your Vita should look like this:
```
   └── UNSI22233/
    ├── Media/
    ├── sce_module/
    ├── sce_sys/
    └── eboot.bin
```
7. When prompted, select **Replace the files in destination**.
8. if you encounter any issues take a look at the [Troubleshooting](#troubleshooting) section
9. Launch the game and enjoy!

---

### Troubleshooting
- Ensure that your PS Vita is properly overclocked.  
- Verify that you have the correct game version (Steam or GOG) and have followed the steps for your version.
- If `ux0:app` does not appear in File Explorer, make sure you have visibility of hidden directories enabled.

---

### Disclaimer
This patch requires a legally purchased copy of UNSIGHTED.


### CONTROLS

| **Button**      | **Action**              |
|-----------------|-------------------------|
| D-Pad Up        | **Aim Lock**             |
| D-Pad Left      | **Heal**           |
| D-Pad Right     | **Reload**          |
| Left Analog Stick | **Move**         |
| Right Analog Stick | **Aim**  |
| L Button        | **Weapon 1**               |
| R Button        | **Weapon 2**              |
| Square Button   | **Run**            |
| Triangle Button | **Interact**       |
| Circle Button   | **Block**               |
| Cross Button    | **Jump**                |
| Select Button   | **Map Map**               |
| Start Button    | **Pause**           |

