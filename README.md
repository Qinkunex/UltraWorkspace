# UltraWorkspace (UltraBar X Desktop Configuration Suite)

[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20(Planned)%20%7C%20Linux%20(Planned)-blue.svg)]()
[![Framework](https://img.shields.io/badge/UI%20Framework-Qt6-green.svg)]()
[![Firmware](https://img.shields.io/badge/LineOS-v1.0.8-orange.svg)]()
[![Documentation](https://img.shields.io/badge/Docs-Official%20Support-brightgreen.svg)](https://hub.sanytron.com/support/ultrabarx)

**UltraWorkspace** is the official desktop configuration software for the **UltraBar X** smart hardware ecosystem. It serves as the control center to design screen layouts, bind physical inputs, configure QuantumLink™ magnetic modules, and deploy context-aware Profiles to your **CoreBAR**.

🔗 **Official Support & Documentation:** [https://hub.sanytron.com/support/ultrabarx](https://hub.sanytron.com/support/ultrabarx)

---

## 📐 System Architecture

UltraBar X is engineered around a **Three-Layer Architecture** to deliver real-time physical response and powerful desktop integration:

+-------------------------------------------------------------------+

| 1. Compute & Data Hub (PC/Mac)                                   |

|    UltraWorkspace Desktop Client (Qt6)                            |

|    - System metrics collection, Profile management, Macros        |

+-------------------------------------------------------------------+

│

USB-C (PCLINK) / Local Wi-Fi (UDP)

│

▼

+-------------------------------------------------------------------+

| 2. Rendering & Driver Engine (CoreBAR)                            |

|    LineOS™ Embedded Operating System                              |

|    - 7" UI rendering, offline automations, smarthome drivers      |

+-------------------------------------------------------------------+

│

QuantumLink™ Magnetic Bus

│

▼

+-------------------------------------------------------------------+

| 3. Physical Interaction Layer (Modules)                          |

|    - VivoCube (OLED Pad)   - KnobKey (Rotary Encoder)              |

|    - DotKey (Macro Keys)   - SenseCube (Environment Radar)        |

+-------------------------------------------------------------------+



> **Note:** Because **CoreBAR** runs its own independent operating system (**LineOS™**), smart home controls, Sonos music playback, and sensor automations remain active even when your PC is sleeping or powered off.

---

## ✨ Key Features

### 1. Context-Aware Profile System
* **Dynamic Workspaces**: Create dedicated Profiles for Coding, Video Editing, Gaming, or Smart Home Control.
* **SceneShift™ Engine**: Automatically switch lighting, audio outputs, and CoreBAR screen widgets when switching PCs via KVM or triggering hotkeys.
* **Export & Backup**: Export setups as `.umpf` files to back up or share with teammates.

### 2. High-Density Touchscreen Widgets
Drag-and-drop widget customization for the CoreBAR 7-inch display:
* **PC Resource Monitor**: Real-time CPU, RAM, storage, and network usage gauges.
* **Smart Productivity**: Pomodoro countdown timer, white noise focus audio, and Todoist/Feishu task sync.
* **Quick Tools**: HotKeys (Win+D, custom combos), Text Input snippets, and Quick Open web/file shortcuts.
* **Weather & Clock**: Flip clocks, multi-timezone World Clocks, and multi-day weather forecasts.

### 3. QuantumLink™ Magnetic Module Management
Easily assign actions to hot-swappable hardware modules:
* **VivoCube**: Configure up to 6 custom display layers with 3 dynamic icon widgets per layer on its 2" circular screen.
* **KnobKey**: Assign left/right rotation for continuous controls (system volume, brush size, timeline scrubbing) and press gestures.
* **DotKey**: Program single-tap, double-tap, and long-press actions or multi-step macro sequences with delay timers.
* **SenseCube**: Configure mmWave radar presence detection (auto sleep/wake) and learn custom desk-tap rhythm triggers.

### 4. Smart Home & Ecosystem Integrations
* **Home Assistant**: Native API integration to control lights, climate, curtains, and run HA automation scenes.
* **Apple HomeKit**: Seamless bridging via Home Assistant for Siri voice control and scene coordination.
* **Sonos & Spotify**: Full music cockpit with live album art display, volume knob control, and multi-room grouping.

---

## 🧩 QuantumLink™ Modules Quick Reference

| Module | Type | Key Features & Functions |
| :--- | :--- | :--- |
| **CoreBAR** | Main Controller | 7.0" Ultra-wide Touchscreen (280×1424), Quad-Core CPU, LineOS™ |
| **VivoCube** | Mini Display Pad | 2.0" Circular AMOLED, up to 6 switchable layers, action bindings |
| **KnobKey** | Precision Controller | Damped metallic rotary encoder + push button for volume/scrubbing |
| **DotKey** | Mechanical Keypad | 3 tactile mechanical switches supporting tap, double-tap, hold, & macro chains|
| **SenseCube** | Environmental Sensor | mmWave presence radar, ambient light, temp/humidity, & tap vibration sensor |

---

## 📦 Downloads & Installation

Visit the **[GitHub Releases](https://github.com/Qinkunex/UltraWorkspace/releases)** page to download the latest builds:

### 🖥️ Desktop Software (Windows)
* **`UltraWorkSpace_Setup_v1.0.0.exe`**: Complete Windows installer package (includes Qt6 runtime and VC++ dependencies).
* **`UltraWorkSpace-v1.0.0-win-x64.zip`**: Portable standalone version (unzip and run `UltraWorkSpace.exe`).

### 📟 Hardware Firmware (OTA)
* **`VivoCube_V2_20260728_ota.bin`**: Binary firmware for VivoCube OTA updates via UltraWorkspace.

### 📱 Android Companion Apps
* **`LineOS_v1.0.8.apk`**: LineOS system application for CoreBAR.
* **`CoreBridge_v1.0.3.apk`**: CoreBridge background service application.

---

## 🚀 Quick Start Guide

1. **Power On**: Connect the DC 12V adapter (or 30W+ USB-C PD charger) to the CoreBAR.
2. **Network Setup**: Follow the on-screen wizard on CoreBAR to connect to your 2.4GHz Wi-Fi network.
3. **Connect to PC**: Connect a data-capable USB-C cable from the CoreBAR PC port to your computer.
4. **Launch UltraWorkspace**:
   * Open UltraWorkspace on your PC and click **New Project**.
   * Click **Search Devices**, select your CoreBAR from the local network list, and click **Add**.
   * Tap **Confirm** on the CoreBAR screen to complete pairing.
5. **Configure & Deploy**: Drag widgets into the central screen simulator, configure module keys, and click **Deploy** in the top right to push settings to your device.

---

## ❓ Frequently Asked Questions (FAQ)

<details>
<summary><b>1. Does UltraBar X work when my PC is powered off?</b></summary>
<br>
<b>Yes.</b> CoreBAR runs its own independent operating system (LineOS™)[cite: 2, 3]. As long as it is connected to power, you can still control Sonos/Spotify audio, trigger Home Assistant smart home scenes, view weather/sensor data, and utilize presence automations without turning on your PC.
</details>

<details>
<summary><b>2. Can CoreBAR be used as a traditional second PC display?</b></summary>
<br>
While the hardware has video input capability, CoreBAR is intentionally designed as an <b>interactive context screen</b> rather than an extended desktop display[cite: 3]. Powered by LineOS™, it proactively pushes real-time system metrics, widgets, and controls to your fingertips without cluttering your main monitor.
</details>

<details>
<summary><b>3. What are the power supply requirements?</b></summary>
<br>
CoreBAR includes a DC 12V adapter with interchangeable US/EU/CN plugs[cite: 1, 3]. You can also power it via USB-C PD (30W or higher required when multiple magnetic modules are attached). Standard 5V/1A phone chargers are insufficient.
</details>

<details>
<summary><b>4. Is Linux support planned?</b></summary>
<br>
<b>Yes.</b> CoreBAR communicates via standard USB HID protocols[cite: 2, 3]. Because UltraWorkspace is built using cross-platform Qt frameworks, native Linux support is on the roadmap following the Windows and macOS releases.
</details>

---

## 📄 License & Contact

* **Official Website**: [https://sanytron.com](https://sanytron.com)
* **Product Support Page**: [https://hub.sanytron.com/support/ultrabarx](https://hub.sanytron.com/support/ultrabarx)
* **Copyright**: © Sanytron. All rights reserved.
