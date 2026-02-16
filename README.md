# 💡 S7-WLED Interface

A lightweight SCL function block for Siemens S7-1200/1500 to control WLED controllers via UDP. 🔌

## ✅ Features
* **Smart Update:** Sends data only on change or 1s heartbeat to save bandwidth. 🔄
* **Color Table:** Uses 20 pre-defined industrial colors for consistent signaling. 🚦
* **Level Support:** Optimized for WLED "Percent" effect (ID 98). 📈
* **Robust:** Integrated array bound checks to prevent CPU stops. 🛡️

## 🛠️ Requirements
* **PLC:** S7-1200 or S7-1500.
* **WLED:** ESP8266/ESP32 with [WLED Firmware](https://github.com/Aircoookie/WLED).

## 🚀 Usage
Import `udtWledCtrl.udt` and `fbWledCtrl.scl`. Use the `TriggerSend` output to drive a `TSEND` block.
<img width="722" height="858" alt="grafik" src="https://github.com/user-attachments/assets/155a1797-81ca-4579-b64a-c990670909f5" />

Configuration TSEND
<img width="1098" height="629" alt="grafik" src="https://github.com/user-attachments/assets/f6197ce1-76cf-4e44-860d-2fe733413a42" />

✍️ Author
G. Jacob | Automation Engineering 🛠️
