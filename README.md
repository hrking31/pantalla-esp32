# 🏠 Smart Home & IoT Ecosystem | Home Assistant

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Platform](https://img.shields.io/badge/Platform-ESPHome%20|%20React-blue)
![Region](https://img.shields.io/badge/Region-Colombia-yellow)

Este repositorio centraliza el ecosistema inteligente de mi hogar, integrando hardware basado en **ESP32/ESP8266** con **ESPHome**, automatizaciones en **Home Assistant** y herramientas personalizadas desarrolladas en **React**.

---

## 🛠️ Proyectos Destacados

### 📡 Gestión de Sensores (IoT)
Nodos distribuidos para el monitoreo ambiental y control de actuadores, optimizados para bajo consumo y comunicación en tiempo real.

- **Monitoreo Multizona:** Gestión térmica de **Sala 1 a Sala 4** con alertas automáticas vía Telegram.
- **Bluetooth Proxy:** Implementación de ESP32 como puente BLE para capturar datos de sensores BTHome v2.
- **Gestión de Energía:** Integración de medidores PZEM-004T para el monitoreo de consumo eléctrico.
- **Control de Iluminación y Extracción:** Nodos dedicados para ventilación automatizada y control de luminarias.

---

## 🌐 Frontend Web (React)

Aplicación web para la visualización y control del sistema IoT en tiempo real.

- Dashboard interactivo con estados de sensores
- Interfaz responsiva con Dark Mode (Tailwind CSS)
- Integración directa con Firebase (Realtime Database, Firestore, Functions, Authentication)

🔗 **Repositorio de la app web:**  
👉 https://github.com/hrking31/alarmas_itx

[![Frontend Repo](https://img.shields.io/badge/Frontend-Alarmas_ITX-0A66C2?style=for-the-badge&logo=react)](https://github.com/hrking31/alarmas_itx)

---

## ⚙️ Tecnologías

- ESP32 / ESP8266  
- ESPHome  
- Home Assistant  
- React.js  
- Tailwind CSS  
- BLE (BTHome)

---

## 🏗️ Arquitectura del Repositorio

```text
📂 ESPHOME/
├── 📂 HomeAssistant/   # Dispositivos (pantalla, extractor, etc.)
└── 📂 AlarmasItx/      # Sensores, alertas y lógica distribuida







    