# BattleBit Remastered AutoHotkey Recoil Control Script

## Table of Contents
- [Introduction](#introduction) - Overview of the script's purpose.
- [Features](#features) - List of key features provided by the script.
- [Prerequisites](#prerequisites) - Necessary requirements before using the script.
- [Getting Started](#getting-started)
  - [Installation](#installation) - Steps to install AutoHotkey and download the script.
  - [Customization](#customization) - Instructions for customizing script settings.
  - [Running the Script](#running-the-script) - How to run the script in your gaming environment.
- [Configuration](#configuration) - Details about customizing the script's behavior.
- [Hotkeys](#hotkeys) - List of hotkeys and their functions.
- [INI File Usage](#ini-file-usage) - How to load and save settings using INI files.
- [Important Notes](#important-notes) - Essential considerations and warnings.
- [Disclaimer](#disclaimer) - Legal disclaimer regarding script usage.

## Introduction

This AutoHotkey script is designed to assist with controlling recoil in BattleBit Remastered. It offers features such as compensating for weapon recoil, controlling pull down rate, and modifying other settings to assist in improving your aiming accuracy. However, please exercise caution and ensure you're adhering to the terms of service of the game you're using this script with.

## Features

- **Recoil Control:** Gain an edge in battles by dynamically adjusting mouse movements to counteract weapon recoil.
- **Fire Rate Control:** Achieve optimal firing rates and accuracy by tweaking the time between shots.
- **Configuration Settings:** Customize the script's behavior to match your gaming environment, including window settings and personal preferences.
- **First Shot Compensation:** Apply pixelX and PixelY adjustments to the first shot to compensate for first-shot recoil.
- **Dynamic Script Naming:** When compiled as an .exe, the script generates unique names for added discretion.

## Prerequisites

Before using the script, make sure you have the following prerequisites:

- [AutoHotkey](https://www.autohotkey.com/download/): This script relies on AutoHotkey, so ensure it's installed on your system.

## Getting Started

### Installation

1. **AutoHotkey Installation**:
   - If you haven't already, download and install AutoHotkey from the [official website](https://www.autohotkey.com/download).
   
2. **Script Download**:
   - Download the [`NoReekoil.ahk`](https://github.com/Silentoplayz/BattleBitNoRecoil.ahk/blob/main/NoReekoil.ahk) file from this repository.

### Customization

- Customize the script's configuration settings according to your gaming preferences. You can adjust key settings such as:
  - **Recoil Adjustments (pixelX and pixelY):** Modify these values to control horizontal and vertical recoil adjustments.
  - **Fire Rate (shotsPerMinute):** Adjust the number of shots fired per minute for optimal fire rate.
  - **Delay Increments (delayIncrement):** Fine-tune the delay between shots by changing this value.
  - **Period (period):** Change the time period for adjustments and actions.
  - **Pixel Increment (pixelIncrement):** Modify the amount by which pixel adjustments change.
  - **First Shot Compensation (firstShotEnabled, firstShotCompensationX, firstShotCompensationY):** Enable or disable adjustments specifically for the first shot fired.

### Running the Script

- Double-click the saved `.ahk` file to run the script.
- The script will only become active when the specified game window process is running.

## Configuration

Unleash the full potential of the script by customizing its settings:

- Explore default configuration values in the script's "Configuration" section.
- Tweak settings such as recoil adjustments, fire rate, delay increments, and more to create your ideal gaming experience.
- Use the script's INI file support to save and load configurations, facilitating easy switches between weapons or scenarios.

## Hotkeys

- The script defines various hotkeys to trigger actions such as adjusting recoil, modifying settings, and more. These hotkeys are active only when the specified game window process is running. Below is a list of some predefined hotkeys and their actions:

  | Hotkey | Action |
  |--------|--------|
  | `Numpad0` | Load settings from an INI file. |
  | `Numpad1` | Save settings to an INI file. |
  | `Numpad2` | Toggle recoil control on/off. |
  | `Numpad3` | Toggle first shot compensation on/off. |
  | `Numpad5` | Cycle through weapons array to dynamically load a weapon config (Vertical Recoil & Shots Per Minute). |
  | `Numpad6` | Decrease pixel adjustments. |
  | `Numpad9` | Increase pixel adjustments. |
  | `Numpad7` | Decrease delay between shots. |
  | `Numpad8` | Increase delay between shots. |
  | `NumpadSub` | Decrease the time period for adjustments. |
  | `NumpadAdd` | Increase the time period for adjustments. |
  | `PgUp` | Increase vertical pixel adjustment. |
  | `PgDn` | Decrease vertical pixel adjustment. |
  | `Del` | Decrease horizontal pixel adjustment. |
  | `End` | Increase horizontal pixel adjustment. |
  | `LButton` | Handle recoil compensation while LButton+RButton on the mouse are held down. |

## INI File Usage

- The script allows you to load and save settings to an INI file, making it easy to customize and switch between different configurations.
- To load settings from an INI file:
   1. Press the `Numpad0` hotkey.
    2. Enter the desired weapon or configuration name when prompted.
    3. The script will load settings from the specified INI section.
- To save settings to an INI file:
    1. Press the `Numpad1` hotkey.
    2. Enter the desired weapon or configuration name when prompted.
    3. The script will save the current settings to the specified INI section.

## Important Notes

- Use this script responsibly and ensure that its usage complies with the terms of service of the game you're playing.
- Always exercise caution when using scripts from external sources to avoid potential security risks or unintended consequences.
- Keep in mind that altering your gameplay experience might lead to ethical considerations, including potential violations of fair play and anti-cheat mechanisms.
- Be aware that AutoHotkey scripts might not work seamlessly with all games due to variations in game engines and anti-cheat implementations.

## Disclaimer

This script is provided "as-is." The developers and contributors accept no responsibility for its usage or any resulting consequences. Please employ this script judiciously and acknowledge associated risks.

## [VirusTotal Scan Results](https://www.virustotal.com/gui/file/cff1bcce92c7e050e5b120056a032dbac2af0f937e2636f53d46f780eaf2ba0f?nocache=1)

Your security matters. The script has been personally scanned with VirusTotal for your peace of mind. You can view the scan results by clicking the [link](https://www.virustotal.com/gui/file/cff1bcce92c7e050e5b120056a032dbac2af0f937e2636f53d46f780eaf2ba0f?nocache=1).

I take the security and trust of my users seriously. Verify the scan results before using the script.
