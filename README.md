# CS2 Autoexec Installation Guide

Enhance your Counter-Strike 2 experience with this pre-made autoexec configuration, designed to optimize your settings and provide useful features like script management. Follow these simple steps to install and setup the autoexec:

**📂 Step 1: Locate Your CS2 CFG Folder 📂**

The CS2 CFG folder is where you'll place the autoexec files. You can find it using either of these methods:

* **Default Location:**
  ```
  Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg
  ```
* **Through Steam:**
  1. Open your Steam Library.
  2. Right-click on Counter-Strike 2.
  3. Select "Properties".
  4. Click on the "Local Files" tab.
  5. Click "Browse". This will open the game's installation folder, and the `cfg` folder will be inside.

**📂 Step 2: Copy and Paste the Files 📂**

1. Download the provided `autoexec.cfg` file and the `AFK` folder.
2. Navigate to your CS2 CFG folder.
3. Copy and paste both the `autoexec.cfg` file and the `AFK` folder into this folder.
4. Feel free to explore and edit the files within the `AFK` folder to customize your AFK settings.

**⚙️ Step 3: Enable the Developer Console & Add Launch Options ⚙️**

1. Open your Steam Library.
2. Right-click on Counter-Strike 2.
3. Select "Properties".
4. Click on the "General" tab.
5. Under "Launch Options", enter the following (make sure to separate each command with a space):
   ```
   -console +exec autoexec.cfg
   ```
6. Click "OK".

**⚙️ Step 4 (Optional): Rebind the Console Key ⚙️**

If your keyboard doesn't have a tilde (~) key or you prefer a different key for the console, you can rebind it through the in-game settings:

1. Launch CS2.
2. Go to "Settings" (gear icon).
3. Navigate to the "Keyboard / Mouse" tab.
4. Scroll down to "Developer Console" and click on the keybind.
5. Press your desired key to rebind it.

**⌨️ Step 5: Execute the Autoexec ⌨️**

1. Launch CS2.
2. Open the developer console using your newly bound key or the tilde (~) key.
3. In the console, type:
   ```
   exec autoexec
   ```
4. Press Enter.

**You're all set!** Your CS2 settings are now optimized with the autoexec. Enjoy your improved gameplay!

