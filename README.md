# Dennis Bosmans

**Full-stack embedded engineer** — firmware to cloud, C++ to JavaScript, hardware to dashboard.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dennis%20Bosmans-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dennis-bosmans-65ab24b/)
[![SmartEGrid](https://img.shields.io/badge/Smart--E--Grid-orange)](https://smartegrid.be)
[![Dots Energy](https://img.shields.io/badge/Dots%20Energy-9652D5)](https://dotsenergy.be)
[![Node-RED](https://img.shields.io/badge/Node--RED-Core%20Contributor-8F0000?logo=nodered&logoColor=white)](https://github.com/node-red/node-red/pulls?q=author%3ADennis-SEG)
[![Devices](https://img.shields.io/badge/3500%2B%20devices%20in%20production-green)](https://smartegrid.be)

---

## What I build

I design and ship the entire stack for energy IoT — from bare-metal ESP32 firmware in C++ to cloud orchestration in Node.js, running on **3500+ devices in production** across Belgium and the Netherlands.

**At [Dots Energy](https://dotsenergy.be)** — smart meter hardware (ESP32-S3) that reads Dutch/Belgian DSMR P1 ports, with NIS2-compliant encrypted transport, remote OTA firmware updates, and built-in Modbus gateways.

**At [Smart-E-Grid](https://smartegrid.be)** — the backend platform that controls solar inverters, batteries, heat pumps and EV chargers in real-time for energy flexibility markets (FCR, aFRR, imbalance).

---

## The stack — fully integrated, all mine

```
┌─────────────────────────────────────────────────────────┐
│  HARDWARE          ESP32-S3 / ESP32-C3 custom PCBs      │
│  FIRMWARE          C++ / FreeRTOS / nanopb / MQTT(S)     │
│  PROTOCOLS         Modbus TCP/RTU, MQTT, SunSpec, DSMR   │
│  OTA               Chunk-based firmware updates + SHA256  │
├─────────────────────────────────────────────────────────┤
│  BACKEND           Node.js / Node-RED / Java             │
│  DEVICE MGMT       3500+ devices, FlowFuse Cloud         │
│  CONTROL           26 custom nodes for energy assets      │
│  REAL-TIME         <10ms grid response, VPP orchestration│
├─────────────────────────────────────────────────────────┤
│  BRANDS            SMA, Huawei, SolarEdge, Sungrow,      │
│                    Fronius, GoodWe, Growatt, Sonnen,      │
│                    Alfen, ETREL                           │
└─────────────────────────────────────────────────────────┘
```

I don't just write firmware or just write backend — I build the **complete pipeline** from the copper trace on the PCB to the API call that dispatches a battery.

---

## Numbers

| | |
|---|---|
| **3500+** | devices in production |
| **26** | custom Node-RED nodes published |
| **<10ms** | grid frequency response time |
| **65%** | bandwidth reduction via binary protocols |
| **10s** | telemetry interval across entire fleet |

---

## Node-RED core contributor

Active contributor to [Node-RED](https://github.com/node-red/node-red) — hardened TCP, UDP, MQTT, WebSocket and Exec nodes against uncaught exceptions in production. Running the largest known FlowFuse Cloud deployment for energy management.

---

## Tech

| Layer | Stack |
|-------|-------|
| **Firmware** | C/C++, FreeRTOS, nanopb, Arduino, ESP-IDF |
| **Hardware** | ESP32-S3, ESP32-C3, STM32, custom PCBs |
| **Protocols** | Modbus TCP/RTU, MQTT/TLS, SunSpec, DSMR P1, OPC UA |
| **Backend** | Node.js, Java, Node-RED, FlowFuse |
| **Data** | InfluxDB, Grafana, FastAPI |
| **Security** | NIS2 compliant, TLS 1.3, SHA256 verification, encrypted OTA |

---

## What I'm working on

- Scaling the fleet from 3500 to 10000+ devices
- Sub-millisecond frequency detection for FCR markets
- Cross-brand Modbus middleware for residential and C&I assets
- Remote device management and OTA at scale

---

**Building the infrastructure that turns every home and business into a grid participant.**
