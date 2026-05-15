# HID Sentinel IR v1.0

**Category:** Incident Response  
**Author:** sucloudflare  
**Target:** Windows 10/11  
**Version:** 1.0

## Description
A lightweight defensive payload that turns your Rubber Ducky into a portable Anti-BadUSB sentinel.  
It detects rogue USB devices in real-time and monitors for suspicious PowerShell activity commonly used in HID attacks.

## Features
- Real-time WMI detection of rogue USB devices (BadUSB / HID Injectors)
- Low-noise behavioral monitoring of PowerShell
- Simple forensic logging (`C:\Windows\Temp\sentinel.log`)

## How to Use
1. Copy `payload.txt` to the root of your USB Rubber Ducky.
2. Insert the device into the target computer.
3. The payload runs automatically and opens the log file.

## Purpose
Designed for ethical use in Blue Team operations, security labs, and Red/Blue Team training exercises.

---

Made for Hak5 Payload Awards
