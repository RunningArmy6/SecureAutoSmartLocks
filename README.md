# 🏛️ SecureAutoSmartLocks (SASL)

### *Colossus Security & Automation Framework*

![Version](https://img.shields.io/badge/Version-2.8.2--Development-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-green?style=for-the-badge)
![Java](https://img.shields.io/badge/Java-21%2B-orange?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Paper/Purpur%201.21%2B-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active%20Development-brightgreen?style=for-the-badge)

**SecureAutoSmartLocks (SASL)** is a Minecraft server-side protection plugin developed by **Protocol-S Development**.

SASL combines automatic container protection, ownership management, persistent lock storage, transfer security and specialized background maintenance systems into a unified architecture.

---

## 🛡️ Core Features

- **Automatic Locking:** Automatically protects supported containers when placed, according to the server configuration.
- **Ownership & Trust Management:** UUID-based ownership and player access management.
- **Structural Synchronization:** Coordinated protection for supported multi-block containers, including double chests.
- **Hybrid Data Management:** Repository-backed YAML storage, Persistent Data Containers (PDC) and in-memory caches.
- **Transfer Security:** Protection mechanisms for hopper-based transfers and hopper minecart interactions.
- **Automated Maintenance:** Background cleanup, cache management and integrity-related operations.
- **Legacy Migration:** LWC migration support through the Colossus Bridge.

---

## ⚙️ Automation Systems

SASL includes specialized automation and transfer-management systems designed to handle ownership and inventory-transfer interactions.

Current implementation includes:

- Hopper ownership tracking.
- Hopper minecart ownership tracking.
- Cached ownership lookups.
- Hopper and hopper-minecart transfer security.
- Memory-aware cache management and cleanup.

**Version compatibility note:** The automation systems are considered most reliable from the **2.8.2+ development line** onward. Earlier versions are legacy implementations and may exhibit less reliable behavior.

[📖 Automation Systems Documentation](https://github.com/RunningArmy6/SecureAutoSmartLocks/wiki/AutomationChain)

---

## 🏛️ Core Engine

The SASL Core Engine contains specialized internal modules responsible for different areas of system operation.

The current architecture includes:

- **Argus**
- **Phoenix**
- **Executioner**
- **Dreadnought**
- **Maximus**

These components work alongside the main plugin architecture to support monitoring, recovery, maintenance, coordination and resource management.

**Version compatibility note:** The current Core Engine implementation uses the **2.8.2+ development line** as its reliability baseline. Earlier versions may contain less mature implementations.

[📖 Core Engine Documentation](https://github.com/RunningArmy6/SecureAutoSmartLocks/wiki/Core-Engine)

---

## 🌉 Colossus Bridge

SASL includes a migration system for importing legacy protection data.

The current migration provider implementation includes **LWC (SQLite)** support.

Migration operations use background processing and validation to reduce the risk of incomplete imports.

> **Important:** Always back up your server and migration database before starting an import. Migration results should be verified before removing the original data.

[📖 Migration Documentation](https://github.com/RunningArmy6/SecureAutoSmartLocks/wiki/Dreadnought-Protocol)

---

## 📚 Documentation

| Documentation | Description |
| :--- | :--- |
| [Installation Guide](https://github.com/RunningArmy6/SecureAutoSmartLocks/wiki/Installation) | Installation and initial configuration. |
| [Automation Systems](https://github.com/RunningArmy6/SecureAutoSmartLocks/wiki/Automation-Systems) | Hopper, hopper minecart and ownership systems. |
| [Core Engine](https://github.com/RunningArmy6/SecureAutoSmartLocks/wiki/Core-Engine) | Overview of SASL's specialist modules. |
| [Migration Protocol](https://github.com/RunningArmy6/SecureAutoSmartLocks/wiki/Migration-Protocol) | Legacy data migration and Colossus Bridge. |
| [Commands & Permissions](https://github.com/RunningArmy6/SecureAutoSmartLocks/wiki/Commands-and-Permissions) | Available commands and authorization. |
| [Storage Architecture](https://github.com/RunningArmy6/SecureAutoSmartLocks/wiki/Storage-Architecture) | Repository, YAML, PDC and cache architecture. |

---

## 📦 Installation

1. Visit the [GitHub Releases](https://github.com/RunningArmy6/SecureAutoSmartLocks/releases) page.
2. Download the latest published `.jar` release.
3. Place the JAR file inside your server's `/plugins` directory.
4. Start the server and configure SASL.

> **Release status:** Version 2.8.2 is under development. The latest published release remains 2.8.1 until the new version is officially released.

---

## 🏛️ About Protocol-S Development

**Protocol-S Development** focuses on Minecraft server infrastructure, protection systems, automation and data management.

- **Project:** SecureAutoSmartLocks
- **Organization:** Protocol-S Development
- **Lead Architect:** RunningArmy6

---

© 2026 Protocol-S Development  
All Rights Reserved. Proprietary Software.
