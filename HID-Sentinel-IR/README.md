# HID Sentinel IR v1.0

**Category:** Incident Response  
**Author:** sucloudflare  
**Target:** Windows 10/11  
**Version:** 1.0

## Description
Lightweight defensive framework against **BadUSB and HID injection attacks**.  
Detects rogue USB devices and suspicious PowerShell activity commonly used in real-world attacks.

## Features
- Real-time WMI detection of rogue USB devices
- Behavioral monitoring of suspicious PowerShell commands
- Simple forensic logging to `C:\Windows\Temp\sentinel.log`

## How to Use
1. Copy `payload.txt` to the root of your Rubber Ducky.
2. Insert the device into the target machine.
3. The Sentinel starts automatically and opens the log file.

**Purpose:** Ethical use in Blue Team operations, labs, and Red/Blue Team training.

---

Made for Hak5 Payload Awards
