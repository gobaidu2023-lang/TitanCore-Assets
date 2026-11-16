# TitanCore Assets & Binary Distribution Node

<p align="center">
  <img src="https://raw.githubusercontent.com/gobaidu2023-lang/TitanCore/main/resources/icons/icon.png" width="96" height="96" alt="TitanCore Logo" onerror="this.style.display='none'"/>
</p>

<p align="center">
  <strong>Official High-Speed Binary Distribution & Mirror Warehouse for TitanCore</strong>
</p>

<p align="center">
  <a href="https://github.com/gobaidu2023-lang/TitanCore"><img src="https://img.shields.io/badge/Main_Project-TitanCore-00f3ff.svg" alt="Main Project"/></a>
  <a href="https://github.com/gobaidu2023-lang/TitanCore-Assets/releases"><img src="https://img.shields.io/github/v/release/gobaidu2023-lang/TitanCore-Assets?color=brightgreen&label=Release" alt="Latest Release"/></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License"/></a>
</p>

---

## 📖 Overview / 仓库概述

This repository serves as the official, decoupled binary distribution endpoint and release mirror for the **TitanCore** ecosystem. It provides verified distribution payloads, engine updates, and global CDN fallback channels to ensure high availability across multi-region networks.

本仓库是 **TitanCore** 官方设立的独立解耦资产分发节点与发布镜像源，专门承载正式版本的免安装更新包、底层引擎组件及多地区全球高可用分发链路。

---

## 📦 Asset Architecture / 资产架构

| Payload Package | Target Component | Description |
| :--- | :--- | :--- |
| `tc{version}.zip` | **TitanCore Client** | Complete portable standalone package for seamless zero-install updates. |
| `ost.zip` | **Engine & Core Dlls** | OST runtime engine package (`xinput1_4.dll`, `OpenSteamTool.dll`, `cloud_redirect.dll`). |

---

## 🚀 CDN & Mirror Accelerators / 镜像加速规范

All release artifacts hosted in this repository can be fetched directly via GitHub Releases or accelerated edge mirrors for domestic optimization:

- **Official Release Channel**:  
  `https://github.com/gobaidu2023-lang/TitanCore-Assets/releases/latest`
- **Fast Edge Mirrors (Mainland China Optimized)**:  
  `https://ghfast.top/https://github.com/gobaidu2023-lang/TitanCore-Assets/releases/download/{tag}/{file}`  
  `https://gh-proxy.com/https://github.com/gobaidu2023-lang/TitanCore-Assets/releases/download/{tag}/{file}`

---

## 🔒 Integrity & Security / 完整性与安全承诺

1. **Automated Pipeline**: All archives are built strictly from the main `TitanCore` CI/CD build trees.
2. **SHA256 Verification**: Hashes are verified by the client runtime before applying any atomic file replacement.
3. **Decoupled Isolation**: Isolated distribution eliminates cross-pipeline contamination.

---

## 📄 License

Distributed under the [MIT License](./LICENSE). Copyright &copy; 2026 TitanCore Project.
