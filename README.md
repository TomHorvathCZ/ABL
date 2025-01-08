# Bypass Android Lockscreen

<p align="center">
<img src="https://img.icons8.com/windows/96/000000/security-document.png">
</p>

<p align="center">
<b>Hm.. New hack ?!</b>
<br>
A worthy successor of the <a href="https://github.com/TomHorvath1607/Android-Bypass-Lockscreen">Android Bypass Lockscreen</a> project
</p>


>⚠️ **Disclaimer**: This tool is for educational and authorized use only. Use it responsibly and only on devices you own or have explicit permission to access. Misuse may result in legal consequences. The authors take no responsibility for any unethical or illegal use.

---

## Features
- Removes lockscreen credentials (PIN, password, or pattern) on compatible Android devices.
- Works in recovery environments (e.g., TWRP) or on rooted devices.
- Clears `locksettings.db` for devices using File-Based Encryption (experimental for Android 10+).
- Lightweight and easy-to-use script.

---

## Compatibility
- **Android Versions**: Tested on Android 4.4 to 9. Experimental support for Android 10+.
- **Custom Recovery**: TWRP or similar recovery environments are required.
- **Root Access**: Optional but required for ADB-based methods.

---

## Installation

### Prerequisites
1. A rooted Android device or a device with custom recovery (e.g., TWRP).
2. Install `busybox` and SQLite tools on the device (for advanced functionality).
3. A computer with `adb` (Android Debug Bridge) installed for manual execution.

### Download
- Download the latest release from the [Releases page](https://github.com/TomHorvathCZ/ABL/releases).

---

## Usage

### Option 1: Flash ZIP in Recovery
1. Download the `ADB2.12.zip` file from the release page.
2. Boot your device into recovery mode (e.g., TWRP).
3. Select **Install** and flash the ZIP file.
4. Reboot the device. The lockscreen should now be bypassed.

### Option 2: ADB Shell (Manual Execution)
1. Extract the script from the ZIP file.
2. Connect your device via USB and enable ADB debugging.
3. Open a terminal and run
   adb shell sh /path/to/unlock_script.sh
