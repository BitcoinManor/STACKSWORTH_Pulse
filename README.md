# STACKSWORTH Pulse ⚡  
### A Touchscreen Bitcoin Node & Monitoring Dashboard

**STACKSWORTH Pulse** is a **5" Raspberry Pi touchscreen Bitcoin dashboard** designed for users who want the option to run a **full Bitcoin node** alongside a local, touch-driven interface for your Bitcoin metrics.

Pulse is the **first touchscreen model** in the STACKSWORTH lineup capable of running a **full Bitcoin node** and hosting a **local SatoNak Hub**, while also providing **monitoring visibility** into a Bitaxe mining setup.

It is built for users who want deeper sovereignty, local data, and hands-on interaction — without replacing or powering other STACKSWORTH devices.

---

## 🔑 What Is Pulse?

STACKSWORTH Pulse combines:
- A touchscreen dashboard
- Optional full-node operation
- A local SatoNak data hub
- Bitaxe farm monitoring (read-only)

Pulse operates as an **independent device** within the STACKSWORTH family.

It does **not** power Matrix or Spark hardware, but may optionally share data via SatoNak endpoints when configured.

---

## 🧠 Core Capabilities

### 🟠 Optional Full Bitcoin Node
- Bitcoin Core (full or pruned)
- Local RPC support
- Sovereign, self-verified blockchain data

Running a node is **optional**, not required.

---

### 🟠 Local SatoNak Hub
- Local API providing Bitcoin metrics such as:
  - Price
  - Block height
  - Miner / pool name
  - Hashrate
  - Difficulty
  - Fees
- Designed for:
  - Local dashboard use
  - LAN-based integrations
  - Development and experimentation

SatoNak may also be run independently on other systems.

---


- SATONAK API'S
  - - - [`Satonak Price`](https://www.satonak.bitcoinmanor.com/api/price)
  - - - [`Satonak Block Height`](https://www.satonak.bitcoinmanor.com/api/height)
  - - - [`Satonak CAD Price`](https://satonak.bitcoinmanor.com/api/price?fiat=CAD)
  - - - [`Satonak Fee`](https://satonak.bitcoinmanor.com/api/fee)
  - - - [`Satonak Hashrate`](https://satonak.bitcoinmanor.com/api/hashrate)
  - - - [`Satonak Circulating Supply`](https://satonak.bitcoinmanor.com/api/circsupply)
  - - - [`Satonak Miner`](https://satonak.bitcoinmanor.com/api/miner)
  - - - [`Satonak 24hr Price Chamge`](https://satonak.bitcoinmanor.com/api/change24h)
  - - - [`Satonak EUR Price`](https://satonak.bitcoinmanor.com/api/price?fiat=EUR)
 

---

## 🚀 Quick Start

- **🔌 Flash Instantly:**  
  [StacksWorth Web Flasher →](https://bitcoinmanor.github.io/STACKSWORTH_WebFlasher) *(custom URL coming soon)*

- **📦 Order Units or Kits:**  
  [stacksworth.com](https://stacksworth.com)

- **🛠 Full Source Code + Firmware:**  
  [STACKSWORTH GitHub](https://github.com/BitcoinManor/STACKSWORTH_Matrix)

- **🎉 Follow Us:**  
  [Twitter/X](https://x.com/BitcoinManor) | [Instagram](https://www.instagram.com/bitcoinmanor/)

---

### 🟠 5" Touchscreen Kiosk UI
- Optimized for Raspberry Pi
- Touch-first navigation
- Modular screen layout
- Always-on kiosk-style display
- Designed for desks, studios, and home setups

---

### 🟠 Bitaxe Farm Monitoring
- View multiple Bitaxe miners
- Display hashrate, temperature, and status
- Monitoring only (no control at this stage)

> Control features are a **future consideration**, not a current promise.

---

## 🧩 Position in the STACKSWORTH Lineup

Pulse is our first **touchscreen model** with expanded capabilities.

| Model | Description |
|-----|------------|
| **Matrix** | Ambient LED Bitcoin ticker |
| **Spark (7")** | Premium touchscreen Bitcoin dashboard |
| **Pulse (5")** | Touchscreen dashboard with optional full-node & Bitaxe monitoring |
| **Edge (7")** | Touchscreen dashboard *(planned)* |
| **Infinity (10")** | Large-format display *(planned)* |

Each device is designed to operate **independently**.

---

## 🛠️ Hardware Overview

- Raspberry Pi (model configurable)
- 5" Touchscreen display
- External or internal SSD (for node data)
- Ethernet-first (WiFi optional)
- Designed for 24/7 operation

> Hardware specifics may evolve.  
> This repository focuses on **software, UI, and system architecture**.

---

## 📁 Repository Structure (Planned)
stacksworth-pulse/ ├── kiosk-ui/          # Touchscreen UI ├── satonak-hub/       # Local API service ├── node/              # Bitcoin Core configuration ├── bitaxe/            # Monitoring modules ├── install/           # Setup & installer scripts ├── docs/              # Architecture & guides └── README.md

---

## 🎯 Design Philosophy

- Bitcoin-first
- Sovereignty by choice
- Local over cloud
- Clear separation of devices
- Conservative feature promises
- Built to expand without dependency
Visit ['BitcoinManor '](https://bitcoinmanor.com) or ['StacksWorth '](stacksworth.com) to buy yours
---

## 🚧 Project Status

**Early active development**

Current focus:
- Repository scaffolding
- UI layout and navigation
- Local SatoNak integration
- Stable node + service operation

---

## 🤝 Contributions

This project is being built in the open.

Feedback, issues, and pull requests are welcome — especially from:
- Bitcoin node operators
- Raspberry Pi builders
- UI/UX contributors
- Bitaxe users

---

## 🧡 Built by Bitcoin Manor

STACKSWORTH is a family-built Bitcoin hardware project focused on making Bitcoin data visible, understandable, and sovereign — without unnecessary complexity or dependency.

More coming soon.
