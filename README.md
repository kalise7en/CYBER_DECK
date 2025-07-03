# CYBER_DECK

The Cyber_Deck is a portable, customizable computing system housed in a weatherproof case. It is built around a Raspberry Pi 5 and designed for independent security auditing and wireless experimentation. The system includes a 10-inch touchscreen, 2TB NVMe SSD for storage, and a 65,000mAh power bank. Running Kali Linux, it supports Wi-Fi and SDR-based testing and monitoring.

---

## Hardware Components

- Raspberry Pi 5 (8GB RAM)
- Official Raspberry Pi 5 Active Cooler with aluminum heatsink and blower
- 10.1" IPS LCD Touchscreen Display (1024x600 resolution)
- 2TB Crucial P3 NVMe SSD in a Dockteck USB 3.2 tool-free enclosure
- 65,000mAh power bank with USB Power Delivery (22.5W)
- MEIJIA all-weather waterproof protective case (15.98" x 12.99" x 6.85")
- Panel-mounted and short cables:
  - Micro HDMI to HDMI (90° angled)
  - USB 3.0 male to female extensions
  - USB-C male to female extension
  - RJ45 Ethernet extension (panel mount)
  - 3.5mm stereo audio extension

---

## Wireless and Radio Adapters

- NooElec Smart V5 SDR for radio frequency analysis
- Panda Wireless PAU0F AXE3000 WiFi 6E adapter (supports monitor mode)

Note: Various online tutorials are available for configuring these adapters with GQRX, GNU Radio, and Airmon-ng.

---

## Power Management Considerations

- The Raspberry Pi 5 requires ~2.7A during boot. To ensure smooth operation without manual intervention, set `max_current_enable=1` in `config.txt`.
- USB PD-compatible power banks are recommended to handle high current demand.
- If using a power bank without a hardware switch, a kill switch can be added inline between the battery and PCB. Only perform such modifications if properly trained, as lithium-ion batteries can be hazardous.

---

## Software and Offline Tools

- **Kiwix** for offline access to large information repositories such as Wikipedia (via ZIM files)
- **Ollama** for running lightweight local LLMs through the terminal
- **Kali Linux** full penetration testing suite

Be sure to update your system before disconnecting from the internet
---

<p align="center"> <img src="https://github.com/user-attachments/assets/a62b2c2b-541a-4fed-be7d-7272fe7cc2f6" width="500"/><br/> <em>External View - Closed Cyber Deck</em> </p> <p align="center"> <img src="https://github.com/user-attachments/assets/dbcd73ae-0d05-49e1-a130-47be137595de" width="500"/><br/> <em>Boot-Up Display Screen</em> </p> <p align="center"> <img src="https://github.com/user-attachments/assets/42e54aaf-c617-4bc3-af82-5a841c22c21d" width="500"/><br/> <em>Internal Wiring and Component Layout</em> </p> <p align="center"> <img src="https://github.com/user-attachments/assets/f6d71703-7592-4716-a841-84c766f7275e" width="500"/><br/> <em>Side View - Ports and Extensions</em> </p> <p align="center"> <img src="https://github.com/user-attachments/assets/e8ee1701-09b4-41d8-b214-b63c13b0c3be" width="500"/><br/> <em>Internal Components - SSD, Pi 5, Power</em> </p> <p align="center"> <img src="https://github.com/user-attachments/assets/abba3c18-c548-422d-9def-ff5de38d7f5c" width="500"/><br/> <em>Touchscreen UI Running Kali</em> </p> <p align="center"> <img src="https://github.com/user-attachments/assets/52b3fb74-cd66-4f00-a588-51794c5be056" width="500"/><br/> <em>Back Panel and Heatsink Fan</em> </p>

