# Scoreboard-V1
A hardware-based scoreboard system controlled via physical remote, with MQTT cloud connectivity.

## 📌 Overview

This is a complete scoreboard system designed for sports events. Unlike V2 (which will use a web dashboard), **V1 is controlled entirely through a physical remote control** with 11 buttons.

### Key Characteristics

- **Physical Remote Control** — 11 buttons for score, timer, penalty, and period control
- **MQTT Cloud Connectivity** — Commands are published to MQTT broker (internet required)
- **Robust Error Handling** — Watchdog timers, error states, auto-recovery
- **Multi-Field Ready** — Designed to support multiple fields (up to 4)
- **No Web Dashboard** — All control is physical, no web interface

### Important: Internet Required

**V1 requires internet connectivity** because it uses MQTT over the internet (via a public or cloud broker like EMQX). There is no offline-first capability in this version.

### Limitations of V1

| Limitation | Why |
|------------|-----|
| Internet required | MQTT broker is cloud-based |
| No web dashboard | All control is physical |
| Single display | One display unit per field |
| No data logging | No persistent storage |

### What V1 Does Well

| Strength | Why |
|----------|-----|
| **Robust** | Watchdog timers, error handling |
| **Reliable** | Data validation, debounce protection |
| **Expandable** | Multi-field support built-in |
| **Professional** | OLED status displays, error states |
| **Documented** | Complete protocol and wiring |

## 🔮 V2 (Planned Upgrades)

| Feature | Description | Status |
|---------|-------------|--------|
| **Web Dashboard** | Browser-based control interface | Planned |
| **Offline-First** | Local network operation | Planned |
| **LoRa Communication** | Long-range wireless | Planned |
| **Custom PCB** | Professional circuit board | Planned |
| **Team Names** | Display team names | Planned |
| **Match Logging** | Save match history | Planned |
| **Tournament API** | Connect to tournament systems | Planned |
