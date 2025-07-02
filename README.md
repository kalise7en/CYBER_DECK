# CYBER_DECK

A portable, customizable PC in a laptop-style architecture. Housed in a weatherproof case, a Raspberry Pi 5, 65,000mAh power bank, 10" touchscreen, and 2TB SSD (USB boot) work together to run Kali Linux and operate as an independent penetration testing tool. With Wi-Fi adapters and an SDR, this machine can perform deauth attacks and scan a wide range of radio frequencies.

---

## 🧰 Hardware

- **Raspberry Pi 5 (8GB)**
- **Pi 5 Official Active Cooler**
- **10.1" IPS LCD Touch Screen** (1024x600)
- **2TB Crucial P3 NVMe SSD** in Dockteck USB 3.2 enclosure
- **65,000mAh PD Power Bank** (22.5W)
- **Weatherproof MEIJIA Case** (15.98"x12.99"x6.85")
- **Cables**: HDMI, USB-C, USB 3.0, 3.5mm audio, Ethernet—all short and panel-mounted where possible

---

## 🛰️ Adapters

- **SDR**: NooElec Smart V5 (radio transmission analysis)
- **Wi-Fi**: Panda PAU0F AXE3000 (WiFi 6E, monitor mode capable)

> *Check YouTube for setup tutorials for GQRX, GNU Radio, and Airmon-ng with these adapters.*

---

## ⚠️ Power Notes

- The Pi 5 draws 27 W at boot. Modify `config.txt` with `max_current_enable=1` to avoid manual startup.
- Ensure the power bank supports USB PD (Power Delivery).
- Some power banks lack a switch. A hardware kill switch was added between the battery cell and PCB (⚠️ only do this if you know what you're doing—Li-ion batteries are dangerous).

---

## 📚 Libraries & Tools

- **Kiwix** (offline Wikipedia + ZIM files for portable reference)
- **Ollama** (terminal-accessible local LLMs)
- **Kali Linux** (full suite preinstalled; update before going offline):
  ```bash
  sudo apt update && sudo apt upgrade -y
