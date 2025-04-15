<p align="center">
  <img src="./docs/icon-512.png" alt="PurpleCabin Logo" width="150" />
</p>

# 🏔️ PurpleCabin – *There are many Cabins on the Mountain*

**PurpleCabin** ist eine Sammlung smarter Tools und Services, die in einem zentralen IoT-Dashboard namens **PurpleMountain** zusammenlaufen.

Ursprünglich für meine eigene Wohnung entwickelt, wächst dieses Projekt nun zu einer vollwertigen Open-Source-Smart-Home-Plattform – mit Fokus auf Flexibilität, Low-Cost-Hardware (z. B. ESP32) und Spaß beim Selbermachen.

---

## ✨ Features

- 🌐 **PurpleMountain Dashboard**: übersichtliche, modulare Oberfläche für alle verbundenen Geräte
- ⚙️ **ESP32-Integration**: einfache Verbindung und Konfiguration über das Dashboard
- 📈 **Live-Daten & Diagramme**: Sensoren, Aktoren, Zustände auf einen Blick
- 🧠 **Automation**: automatische Abläufe & Zeitsteuerung
- 🔒 **Tailscale-ready**: sicherer Zugriff auf dein Smart Home – auch unterwegs
- 💾 **Datenbankgestützt**: alles in MySQL gespeichert & analysierbar
- 🎛️ **Responsive Web-Oberfläche**: optimiert für Desktop, Tablet und iOS-PWA

---

## 🧰 Technologien

- 🐳 Docker & Docker-Compose
- ⚙️ Node.js (Backend)
- 🐬 MySQL
- 📦 Nginx (Reverse Proxy)
- 🧠 ESP32 (Arduino IDE + WiFi/Bluetooth)
- 🧭 Tailscale (Zero-Config VPN)
- 🎨 HTML, CSS, JavaScript (Frontend)

---

## 🚀 Installation (Quickstart via Docker)

```bash
git clone https://github.com/PurpleCabin/PurpleMountain.git
cd PurpleMountain
cp .env.example .env  # Passe deine Umgebungsvariablen an
docker-compose up -d
