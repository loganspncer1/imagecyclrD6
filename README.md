# Fifine D6 Image Cycler

A plugin for the Fifine D6 Stream Dock that allows you to personalize a button that changes images when clicked. You can change among multiple icons or blink them, while with one click you can also trigger hotkeys. It features an integrated image editor that will allow you to crop and zoom your icons to perfection.

Features

* **Multi-State Icons:** Toggle between 2 or 3 different images on a single click.
* Flashing Mode: Convert buttons into animated alerts with adjustable speeds.
* **Built-in Editor:** Crop, pan, and zoom images directly within the plugin to fit the D6 keys.
* **Pro Hotkeys:**
* Record complex key combinations.
* **Hold Support:** Specify keys to be held down for a certain duration in ms.
* **Trigger Control:** Fire hotkeys once on start or continuously with every cycle.

* **State Management:** Ability to automatically reset to the default icon once flashing has stopped.

Installation
1. **Download** the most recent release folder (`com.logan.imagecycler.sdPlugin`).
2. **Close** your Fifine Stream Dock software completely (check the system tray).
3. **Navigate to your plugins folder:
*   `%APPDATA%\HotSpot\StreamDock\plugins\`
*   *(Typically C:\Users\YourName\AppData\Roaming\HotSpot\StreamDock\plugins\)*

4. **Copy** the folder `com.logan.imagecycler.sdPlugin` into this directory.

5. **Restart** the Stream Dock software.

> **Note:** If you utilize the "Hold" hotkey feature for games or admin apps, please run the Stream Dock software as **Administrator**.
## Usage
1. Setting up Images

*   Select **Image Count**: Choose either 2 or 3 images.
* Click **Choose Image** to select a file (`.png`, `.jpg`, `.ico`).
*   In the **Editor** window, zoom and pan so that the image fits the square exactly, then click **Save**

2. Modes
**Toggle Cycle**

* Standard mode. Clicking on the button changes to the next image in the list.
* Great for Mute toggles, On/Off switches, or status indicators.
Flashing Mode
* Animated mode. Pressing the button starts cycling through images automatically at the set **Speed**.
*   **On Stop:** Select whether the icon remains on the last image or goes back to **Default**.
3. Hotkeys
* Click the **Hotkey** box and press your key combination, such as Ctrl + Shift + M, to record it.

*   **Hold (ms):

*   Set to `0` for a standard tap.
* Set to a higher number, e.g., `500` to hold the key down for that many milliseconds. * **On Cycle:** * **Fire Once:** Triggers the hotkey only upon the first press of a button. *   **Fire Everytime:** Triggers the hotkey every time the image changes. Useful for rapid-fire macros. License This project is licensed under the [MIT License](LICENSE). Copyright (c) 2025 Logan
