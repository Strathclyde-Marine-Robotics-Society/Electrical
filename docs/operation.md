# 🧭 Operation & Maintenance Manual

This guide describes how to use and maintain the robotic vessel.

---

## 1. Getting Started

### Powering On
1. Connect battery securely.
2. Wait ~30 seconds for Raspberry Pi to boot.

### WiFi Access
- SSID: `Vessel_AP`
- IP: `192.168.4.1`
- Open browser to control: `http://192.168.4.1/control`

---

## 2. Modes of Operation

### Manual Mode
- Web joystick interface for manual control
- Requires connection to onboard WiFi

### Autonomous Mode
1. SSH into Raspberry Pi
2. Upload `waypoints.csv`
3. Run:
   ```bash
   python3 main.py --auto
