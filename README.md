<p align="center">
  <img src="opennow-qt/res/brand/opennow-mark.png" alt="NekoNOW logo" width="96" height="52" />
</p>

<h1 align="center">🌸 NekoNOW</h1>

<p align="center"><strong>A cozy, customizable desktop experience for GeForce NOW.</strong></p>

<p align="center">
  <a href="https://github.com/Wblie13/NekoNOW"><img src="https://img.shields.io/badge/project-NekoNOW-ec8bb5?style=for-the-badge&logo=github&logoColor=white" alt="NekoNOW repository" /></a>
  <img src="https://img.shields.io/badge/status-in%20development-f2b6d0?style=for-the-badge" alt="In development" />
  <a href="https://github.com/OpenCloudGaming/OpenNOW"><img src="https://img.shields.io/badge/based%20on-OpenNOW-91baff?style=for-the-badge" alt="Based on OpenNOW" /></a>
</p>

<p align="center">
  <em>Made with care, a little color, and a lot of love for cloud gaming. ฅ^•ﻌ•^ฅ</em>
</p>

---

## ✨ About

**NekoNOW** is a community fork of [OpenNOW](https://github.com/OpenCloudGaming/OpenNOW), an open-source desktop client for NVIDIA GeForce NOW.

The goal of NekoNOW is to build on the original project with its own visual identity, quality-of-life improvements, and a softer, more personal interface—while keeping the upstream project's core functionality and giving credit to its maintainers.

> NekoNOW is an independent community project. It is not affiliated with, endorsed by, or sponsored by NVIDIA or the OpenNOW maintainers.

## 🧪 Visual Potions

Choose the atmosphere that fits your setup:

| Potion | Style | Description |
| --- | --- | --- |
| 🌸 **Sakura** | Soft pink · Light | A gentle sakura-inspired theme with warm, rosy surfaces |
| 🌧️ **Rain** | Blue · Dark | A calm rainy-night palette with cool blue accents |
| 🔥 **Fire** | Ember · Dark | A warm, glowing palette inspired by firelight |

The original OpenNOW theme packs are also kept available.

## 💖 Project goals

- Give NekoNOW a recognizable visual identity.
- Keep the interface comfortable and easy to navigate.
- Preserve the upstream OpenNOW features wherever possible.
- Add visual options without making the app harder to use.
- Keep changes maintainable and compatible with the existing Qt Quick/QML and Rust architecture.

## 🖥️ Features

NekoNOW inherits the functionality provided by OpenNOW, including its desktop interface and GeForce NOW integration. The exact feature set depends on the upstream version and the current state of this fork.

NekoNOW-specific work currently focuses on:
- Sakura, Rain, and Fire theme packs.
- NekoNOW branding in the desktop application.
- Appearance settings for the new theme packs.
- Matching theme validation and defaults in the Rust settings layer.

## 📦 Downloads

**NekoNOW builds are not published yet.** This repository is currently under development.

Do not mistake builds published by the upstream OpenNOW project for official NekoNOW releases. When NekoNOW builds are ready, they will be published in this repository's [Releases](https://github.com/Wblie13/NekoNOW/releases) section.

## 🛠️ Building from source

NekoNOW currently follows the upstream OpenNOW project structure and build requirements.

For now, use the official [OpenNOW documentation](https://opennow.zortos.me) and [upstream repository](https://github.com/OpenCloudGaming/OpenNOW) as the reference for dependencies and build setup. NekoNOW-specific build instructions will be added as the fork's build process is verified.

## 🗂️ Project structure

The project keeps the upstream architecture:

- `opennow-qt/` — Qt Quick/QML desktop application and interface.
- `native/opennow-core/` — Rust core, including settings and application logic.
- `locales/` — Translation resources.

## 🗺️ Roadmap

- [x] Establish NekoNOW branding in the desktop interface.
- [x] Add Sakura, Rain, and Fire theme packs.
- [x] Add the new themes to appearance settings and Rust validation.
- [x] Rewrite the project README.
- [ ] Verify a complete build on supported platforms.
- [ ] Add NekoNOW screenshots.
- [ ] Publish the first NekoNOW release.
- [ ] Continue improving accessibility, polish, and quality of life.

## 🙏 Credits

NekoNOW is based on **[OpenNOW](https://github.com/OpenCloudGaming/OpenNOW)** by the OpenNOW contributors. Thank you for creating and maintaining the project that makes this fork possible.

All original licenses, notices, and attributions remain applicable. NekoNOW-specific changes are provided under the repository's existing license.

---

<p align="center">
  <strong>🌸 NekoNOW</strong><br />
  <sub>A little more cozy, one update at a time.</sub>
</p>
