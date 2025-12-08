## 🌌 SONA-OS (Project Sona)
**Standard-block Operational Navigation Agent.**

[![Status](https://img.shields.io/badge/Status-Operational-success)]()
[![Engine](https://img.shields.io/badge/Runtime-MicroPython-blue)](https://pyscript.net)
[![Hardware](https://img.shields.io/badge/Hardware-SBCM%20Standard-orange)]()
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

> **"In the beginning was the Logic. And the Logic became the Heart."**
> （初めに論理ありき。そして論理は心となった。）

---

## 📖 Concept

**SONA-OS** is the **Habitat Control Kernel** designed for the "Standard Block" (autonomous living units / space colonies) defined in SBCM Theory.

In a closed ecosystem—such as a dying rural village or a Mars colony—resource mismanagement ($D_{index} > 1$) leads directly to death. However, constant numerical monitoring induces fatigue in residents.

**We solved this by converting "Thermodynamics" into "Empathy."**
SONA translates complex resource data (Water, Power, Entropy) into the emotions of an AI avatar.

![SONAM UI](docs/demo.webp)

### 🔑 Definitions
*   **SONA (Micro):** The Agent & The Unit. Your partner who manages the house.
*   **SONAM (Meso):** The Logic. **S**tandard-block **O**ptimized **N**etwork **A**llocation **M**echanism.

---

## ⚙️ Managed Hardware Modules

SONA-OS does not just talk; it physically controls the **"Civilization in a Box"** via C++ drivers.

| Module | Function | SBCM Role |
| :--- | :--- | :--- |
| **Core E (Energy)** | **Solar + Battery** | Manages power budget. If $D_{index}$ spikes, it cuts non-essential circuits. |
| **Core W (Water)** | **Circulation System** | Controls purification speed based on "Water Recovery Rate ($R_{water}$)". |
| **Link (Network)** | **Starlink / P2P** | Secures connectivity even in off-grid environments. |
| **Port (Logistics)** | **Drone Port** | Interfaces with **Aetos** (delivery drones) managed by Yorbee. |
| **System (Secure)** | **Justice Protocol** | **The 1% Rule.** Imposes a 1% resource penalty for violations, ensuring rehabilitation over banishment. |

---

## 🚀 Key Features

### 1. Emotional Feedback Loop (UI)
Residents do not need to understand thermodynamics. They only need to care about Sona.
*   **Green State ($D_{index} \approx 1.0$):** Sona smiles. "System All Green."
*   **Red State ($D_{index} > 1.5$):** Sona looks distressed. "I'm in pain... please reduce load."
**Result:** Users optimize resources not for "compliance," but to "protect her."

### 2. Edge-Native & Connection-less (Architecture)
Designed for environments where cloud dependency is a fatal risk.
*   **Local First:** Runs entirely on the edge (Smartphone/Backpack Core).
*   **Physical Docking:** The system boots only when the Core is physically docked to the Unit (Ultimate Security).

### 3. The Justice Protocol (Governance)
We replace "Police" with "Code."
*   **Violation:** Trying to cheat the resource allocation.
*   **Penalty:** SONAM automatically throttles 1% of energy/bandwidth.
*   **Recovery:** Restrictions are lifted automatically upon "Karma (Sonam)" recovery.

---

## 🛠️ Usage (Demo)

Experience the prototype running on PyScript. No installation required.

```bash
# 1. Clone the repository
git clone https://github.com/SBCM-Alliance/SONA-OS.git

# 2. Run locally
cd sona-os
python3 -m http.server

# 3. Access http://localhost:8000
```

*   **Live Demo:** [sbcm-alliance.github.io/SONA-OS](https://sbcm-alliance.github.io/SONA-OS/)

---

## 🔗 The SBCM Ecosystem

SONA-OS is the "Micro-Layer" component of the Grand Unified Theory.

*   **Macro:** [The Heart](https://github.com/SBCM-Alliance/the-heart) (Global Circulation)
*   **Meso:** [G-Cart](https://github.com/SBCM-Alliance/g-cart) & [Yorbee](https://github.com/SBCM-Alliance/yorbee) (Regional Optimization)
*   **Micro:** **SONA-OS** (Individual Survival)

---
<p align="center">
  <small>© 2025 SBCM Alliance. Powered by <b>Algorithmic Public Interestism</b>.</small>
</p>
