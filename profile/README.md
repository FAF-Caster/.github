# 🎙️ FAF Caster

### Live statistics, broadcast overlays and companion tools for Forged Alliance Forever.

**FAF Caster** is an open-source project focused on improving the casting and spectator experience for [Forged Alliance Forever](https://www.faforever.com/).

Our goal is to provide casters, tournament organisers and content creators with accessible, real-time match information and broadcast-ready tools.

From detailed player statistics to OBS overlays, FAF Caster aims to make competitive FAF broadcasts more informative, engaging and professional.

---

## 🚀 Our Projects

### 🖥️ FAF Caster Desktop

**The central companion application for FAF casting.**

The Windows desktop application brings together live telemetry, match statistics and broadcast tools in a single interface.

**Key features:**
- Live match telemetry and player statistics
- Economy, military and combat information
- Player comparisons and match monitoring
- Local telemetry Bridge
- React-based statistics dashboard
- OBS-compatible browser overlays
- Portable Windows application

**Repository:** [FAF-Caster/FAF-Caster](https://github.com/FAF-Caster/FAF-Caster)

**Downloads:** [Desktop Releases](https://github.com/FAF-Caster/FAF-Caster/releases)

### 🎮 FAF Caster Bridge — UI Mod

**The connection between Forged Alliance Forever and the desktop companion.**

FAF Caster Bridge is a lightweight, UI-only mod designed to collect supported observer information and make it available to the companion application.

**Key features:**
- Observer-focused telemetry
- Player and army information
- Economy and unit statistics where supported
- Integration with the local FAF Caster companion
- Designed for casting and tournament observation

The mod is developed separately from the desktop application and does not require changes to the FAF game client.

**Repository:** [FAF-Caster/faf-caster-ui-mod](https://github.com/FAF-Caster/faf-caster-ui-mod)

**Downloads:** [UI Mod Releases](https://github.com/FAF-Caster/faf-caster-ui-mod/releases)

---

## 🏗️ How It Works

```text
       Forged Alliance Forever
                 |
                 v
       FAF Caster Bridge
           (UI-only mod)
                 |
                 v
       Local Telemetry Bridge
             (.NET 10)
                 |
                 v
       FAF Caster Dashboard
          (React / TS)
                 |
          +------+------+
          |             |
          v             v
     Desktop App    OBS Overlays
```

FAF Caster uses a modular architecture, allowing the UI mod, local telemetry service and broadcasting tools to be developed independently.

## 📦 Getting Started

1. Download the latest **FAF Caster Desktop** release.
2. Extract the portable Windows application.
3. Download and install the **FAF Caster Bridge** UI mod.
4. Enable the mod in Forged Alliance Forever.
5. Launch FAF Caster Desktop and follow the available connection instructions.

*FAF Caster is under active development. Features and compatibility may change between releases.*

## 🔄 Development and Releases

We use a structured Git branching and release process.

| Branch | Purpose |
|---|---|
| `develop` | Active development, improvements and testing |
| `main` | Stable, release-ready code |
| `feature/*` | Individual features and fixes |

GitHub Actions automates build validation, packaging, versioning and GitHub Releases.

Stable releases use the **`vYY.MM.N`** versioning convention, such as `v26.11.0`.

## 🤝 Contributing

FAF Caster is an open-source community project. Contributions, bug reports, feature suggestions and improvements are welcome.

You can get involved by exploring the repositories, opening issues, discussing improvements or submitting pull requests.

## ⚖️ Disclaimer

FAF Caster is an independent community project and is not an official product of Forged Alliance Forever, the FAF Association, Gas Powered Games or Square Enix.

All relevant game names and trademarks belong to their respective owners.

---

**Built for the FAF community. Made for better casting.** 🎙️
