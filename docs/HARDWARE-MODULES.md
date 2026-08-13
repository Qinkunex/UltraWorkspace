# QuantumLink™ Magnetic Modules Configuration Guide

UltraBar X uses the **QuantumLink™ Magnetic Bus** to instantly recognize hot-swappable modules. Each module can be independently configured in UltraWorkspace.

---

## 1. VivoCube (OLED Display Pad)

**VivoCube** features a 2.0" circular AMOLED display with dynamic interactive layers.

* **Multi-Layer Navigation**: Supports up to **6 customizable screen layers**. Switch between layers using gesture swipes or binding layer-toggle actions to KnobKey/DotKey.
* **Widget Assignment**: Each layer supports up to 3 widget slots (e.g., CPU load gauge, clock, custom image/GIF, or action shortcuts).
* **Configuration Steps**:
  1. Click on **VivoCube** in the UltraWorkspace visual layout.
  2. Select a Layer tab (Layer 1 – Layer 6).
  3. Drag widgets from the right panel into the circular canvas.
  4. Click **Deploy** to push settings to CoreBAR.

---

## 2. KnobKey (Precision Rotary Encoder)

**KnobKey** provides tactile stepless rotation with an integrated push button.

* **Rotation Actions**: Assign separate actions for **Clockwise (CW)** and **Counter-Clockwise (CCW)** turns.
  * *System Volume*: Volume Up / Volume Down.
  * *Creative Apps*: Brush Size, Timeline Scrubbing, Canvas Zoom.
* **Button Actions**: Supports Press and Hold gestures (e.g., Mute/Unmute, Play/Pause).

---

## 3. DotKey (Mechanical Keypad)

**DotKey** consists of 3 tactile mechanical switches for rapid execution.

* **Gesture Triggers**: Each key supports 3 distinct trigger modes:
  * **Single Tap**: Quick execution (e.g., Mute Mic, Win+D).
  * **Double Tap**: Secondary shortcuts.
  * **Long Press**: Hold actions or complex sequences.
* **Macro Chains**: Assign custom macro sequences with programmable millisecond delay timers between keystrokes.

---

## 4. SenseCube (Environmental Radar)

**SenseCube** integrates mmWave radar and environment sensors for context-aware automation.

* **Presence Auto-Sleep/Wake**: Configures CoreBAR screen brightness based on user proximity. Automatically dims or sleeps when you step away from the desk.
* **Desk-Tap Rhythm Triggers**: Uses vibration sensing to detect user desk taps. Bind double-tap on desk to trigger smart home lights or toggle focus audio.
