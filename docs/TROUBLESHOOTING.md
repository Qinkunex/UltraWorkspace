# Troubleshooting & Frequently Asked Questions (FAQ)

## 1. UltraWorkspace Closes Immediately After Launch (Windows)

* **Cause**: Windows restricts non-administrator write permissions inside `C:\Program Files`. If the app attempts to write local configuration/logs to its install folder, it flashes and exits.
* **Solution**:
  1. Ensure you are using installer **v1.0.0+** with `Permissions: users-full` enabled.
  2. Alternatively, right-click `UltraWorkSpace.exe` → **Properties** → **Compatibility** → Check **"Run this program as an administrator"**.

---

## 2. UltraWorkspace Cannot Discover CoreBAR on Local Network

* **Cause**: CoreBAR and PC are on different Wi-Fi subnets, or Windows Firewall is blocking UDP local discovery.
* **Checklist**:
  * Verify CoreBAR and PC are connected to the same 2.4GHz Wi-Fi router.
  * Check Windows Defender Firewall settings and allow `UltraWorkSpace.exe` through Private networks.
  * If wireless discovery fails, connect CoreBAR to PC directly using a USB-C data cable.

---

## 3. Screen Flickers or Modules Disconnect Randomly

* **Cause**: Insufficient power delivery via standard USB ports.
* **Solution**:
  * CoreBAR requires **DC 12V adapter** (included) or a **USB-C PD charger supporting 30W+**.
  * Avoid plugging CoreBAR into unpowered USB hubs or standard 5V/1A motherboard ports when multiple magnetic modules (VivoCube, SenseCube) are attached.

---

## 4. Smart Home Commands Work When PC is Off?

* **Yes**. CoreBAR runs independently on **LineOS™**. As long as DC/PD power is maintained and Wi-Fi remains connected, Home Assistant scenes, Sonos music playback, and SenseCube presence radar automations stay active even if your PC is powered off.
