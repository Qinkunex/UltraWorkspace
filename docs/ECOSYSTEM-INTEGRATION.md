# Ecosystem & Smart Home Integrations Guide

CoreBAR runs **LineOS™**, an embedded operating system that directly executes driver protocols and smart home commands locally without depending on PC software.

---

## 1. Home Assistant Integration

Integrate your entire smart home setup into CoreBAR screens and physical switches.

### Setup Steps:
1. Open **UltraWorkspace** → Go to **Settings** → **Smart Home** → **Home Assistant**.
2. Enter your **Home Assistant URL** (e.g., `http://192.168.1.100:8123`).
3. Generate a **Long-Lived Access Token** in Home Assistant (User Profile → Long-Lived Access Tokens) and paste it into UltraWorkspace.
4. Click **Test Connection**. Once successful, entity lists (lights, switches, scenes, climate) will populate automatically.
5. Drag Home Assistant entity widgets onto CoreBAR or bind them to DotKey/KnobKey physical controls.

---

## 2. Sonos & Spotify Music Control

Transform CoreBAR into a dedicated desktop music cockpit.

* **Real-time Album Art**: Displays current playing song, artist, and high-res cover art on the 7" screen.
* **Hardware Sync**: Rotate **KnobKey** to adjust Sonos volume; tap **DotKey** to skip tracks or switch multi-room audio groups.
* **PC-Independent Playback**: Control Sonos speakers directly over Wi-Fi, even when the host PC is shut down.
