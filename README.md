# CS2 Autoexec Installation Guide

Enhance your Counter-Strike 2 experience with this pre-made autoexec configuration, designed to optimize your settings and provide useful features like script management. Follow these simple steps to install and setup the autoexec:

**📂 Step 0: Downloading and Extracting the Files 📂**

1. Navigate to the GitHub repository containing the autoexec files.
2. Click on the green "Code" button and select "Download ZIP".
3. Extract the downloaded ZIP file to a location of your choice. This will create a folder containing the necessary files. For CS2 you want the contents inside the CS2 folder.
   
**Note:** CSGO and my autoexec for it is now deprciated and is only here for legacy reasons.
   
**📂 Step 1: Locate Your CS2 CFG Folder 📂**

The CS2 CFG folder is where you'll place the autoexec files. You can find it using either of these methods:

* **Default Location:**
  ```
  Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg
.  ```
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

## CS2 Keybind Guide

A comprehensive list of keybinds used in the provided autoexec configuration. You can customize these to your preferences within the `binds.cfg` file in the `AFK` folder.
**default mouse sens is 1.0**
**Weapon & Equipment Binds**

| Key             | Action                                            |
|----------------|---------------------------------------------------|
| 1 / Mouse Wheel Up | Equip primary weapon                                            |
| 2 / Mouse Wheel Down | Equip secondary weapon (pistols)                                |
| 3               | Equip knife, Zeus, or hands (Danger Zone)                       |
| 4 / X           | Equip incendiary/Molotov grenade                                  |
| 5               | Equip C4 explosive or Medi-Shot                                  |
| C               | Equip high explosive grenade or snowball                         |
| F               | Equip flashbang                                                  |
| Q               | Equip smoke grenade                                               |
| -               | Equip Zeus (buy menu)                                              |
| =               | Equip Medi-Shot (buy menu)                                         |

**Movement & View Binds**

| Key             | Action                                                            |
|----------------|-------------------------------------------------------------------|
| A               | Strafe left                                                     |
| D               | Strafe right                                                    |
| S               | Move backward                                                   |
| W               | Move forward                                                    |
| Shift           | Walk                                                           |
| Space           | Jump (hold for high jump with ExoJump Boots in Danger Zone)      |
| Ctrl            | Duck/Crouch                                                     |
| Mouse X/Y       | Control view (yaw/pitch)                                         |
| Arrow Keys       | Control movement/view                                             |

**Communication & Utility Binds**

| Key             | Action                                                            |
|----------------|-------------------------------------------------------------------|
| U               | Team chat                                                       |
| Y               | All chat                                                        |
| Z               | Radial radio menu                                                |
| B               | Open buy menu/tablet delivery (Danger Zone)                     |
| E               | Use (with beep sound)                                              |
| G               | Drop weapon                                                     |
| H               | Open spray menu                                                  |
| Mouse3          | Player ping                                                    |
| Mouse4          | Voice chat (hold to speak)                                        |
| N               | Jumpthrow grenade                                               |
| P               | Toggle X-ray in spectator mode                                  |
| Mouse5          | Quick switch to knife/Zeus                                        |
| R               | Reload                                                          |
| Tab             | Show scoreboard/tablet (Danger Zone)                            |

**Function Key & Other Binds**

| Key             | Action                                                            |
|----------------|-------------------------------------------------------------------|
| ` (tilde)       | Toggle console                                                   |
| ,               | Execute autoexec.cfg                                             |
| .               | Execute config.cfg                                              |
| F4              | Toggle AFK auto-walk                                            |
| F5              | Toggle clutch mode (mute teammates)                             |
| F6              | Toggle enemy team communication (mute)                          |
| F7              | Toggle chat messages (mute)                                     |
| F8              | Toggle radio messages                                            |
| F9              | Execute "fixer" script                                          |
| PgUp            | Execute default audio settings                                   |
| PgDn            | Mute sound                                                      |


**Numpad Binds (Buy Menu)**


| Key             | Action                                                            |
|----------------|-------------------------------------------------------------------|
| KP_Divide       | Buy HE grenade                                                 |
| KP_Multiply     | Buy flashbang                                                   |
| KP_Minus        | Buy smoke grenade                                                |
| KP_Plus         | Buy incendiary/Molotov grenade                                   |
| KP_Enter        | Buy defuse kit                                                  |
| KP_Del          | Buy kevlar vest                                                 |
| KP_0            | Buy kevlar + helmet                                              |
| KP_1-9          | Buy various weapons/equipment                                    |
