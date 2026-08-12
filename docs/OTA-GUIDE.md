# Module Firmware OTA Update Guide

> **Note:** Firmware updates for all QuantumLink™ magnetic modules (except CoreBAR) are performed manually by selecting local firmware files in UltraWorkspace. The following procedure uses **VivoCube** as an example.

---

### Step 1: Download the OTA Firmware File
Visit the [Official Sanytron Support Page](https://hub.sanytron.com) or download the latest OTA firmware file (`.bin`) directly from GitHub Releases:
* 📥 **[Download VivoCube Firmware (`VivoCube_V2_20260728_ota.bin`)](https://github.com/Qinkunex/UltraWorkspace/releases/download/v1.0.0/VivoCube_V2_20260728_ota.bin)**

---

### Step 2: Perform the Module Upgrade

1. **Locate Module**: Launch **UltraWorkspace**, locate the **VivoCube** module in the device layout, and **right-click** on it.
   <img width="415" height="115" alt="1" src="https://github.com/user-attachments/assets/e187486a-2cd3-4876-b0da-07d2a03ecb34" />
2. **Open Device Management**: Click **Detail** from the pop-up context menu to enter the Device Management page.
   <img width="830" height="252" alt="2" src="https://github.com/user-attachments/assets/f5c8fe13-f452-4672-86f9-327fb6f0cfcc" />
3. **Navigate to OTA**: Select the **OTA** tab.
   <img width="416" height="211" alt="3" src="https://github.com/user-attachments/assets/8a050f72-b529-4546-8c70-e5100564d88b" />
4. **Load Firmware File**: Click to select the downloaded VivoCube `.bin` firmware file from your local drive. The system will automatically read and display the firmware details and configuration metadata.
   <img width="831" height="475" alt="4" src="https://github.com/user-attachments/assets/20b04d27-f6a7-448b-8052-2a3110078a70" />
5. **Start Firmware Flashing**: Click **Start OTA** to begin the flashing process. Wait until the "OTA Upgrade Successful" prompt appears.
   <img width="415" height="223" alt="5" src="https://github.com/user-attachments/assets/f11bf98d-29ab-4e1b-93b9-6fc26b62a590" />
6. **Verify Upgrade Result**: Check the **App Ver** (Application Version) displayed on the VivoCube interface. If it matches the target firmware version number, the upgrade has been completed successfully.
