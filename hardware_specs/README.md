# 🏗️ Sona Hardware Specifications (v0.1 Draft)

## 🏠️ Temporary assembly
![](/hardware_specs/sona_drawio_Temporary.png)

## 🔌 Sona Universal Link (SUL)
**The Physical API for Civilization.**

Sonaハビタットにおける、モジュール間接続の物理標準規格（SBCM-DIN-001）案です。
誰でも、どこでも、安価な資材で再現可能な「単純さ」を最優先に設計されています。

![Sona Universal Link](/hardware_specs/sona_link_concept_v0.1.png)

### 📐 Dimensions (Target Spec)
*   **Module Face:** 200mm × 200mm (Standard Brick Size)
*   **Center Port (Sewage/Structure):** Φ100mm
    *   Role: Gravity drainage, Structural core, Maintenance access.
*   **Top-Left Port (Power/Data):** Φ50mm
    *   Role: Non-contact power transmission, Optical communication.
*   **Top-Right Port (Water):** Φ50mm
    *   Role: Clean water supply (insulated).

### 🛡️ Features
1.  **Poka-yoke Design (Error Proofing):**
    *   非対称な配置（ミッキーマウス型）により、上下逆さまの誤接続を物理的に防止します。
2.  **Gravity First:**
    *   最も詰まりやすい下水（重力流）を中心に最大径で配置。
3.  **Separation:**
    *   水漏れリスクのある配管よりも上部に電気系統を配置し、ショートを防ぎます。

---
> **Note:** This specification is a Concept Draft (v0.1).
> Precise parametric data and CAD files will be updated by the community.
