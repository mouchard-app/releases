<p align="center">
  <img src=".github/assets/icon.png" width="128" alt="Mouchard icon">
</p>

<h1 align="center">Mouchard</h1>

<p align="center">
  A minimal native macOS HTTP/HTTPS debugging proxy.<br>
  See every request and response of your Mac, your iPhone and your simulators, decrypted.
</p>

<p align="center">
  <a href="https://github.com/mouchard-app/releases/releases/latest/download/Mouchard.dmg"><img src="https://img.shields.io/badge/Download-Mouchard.dmg-2ea44f?style=for-the-badge&logo=apple&logoColor=white" alt="Download Mouchard.dmg"></a>
</p>

<p align="center">
  <a href="https://github.com/mouchard-app/releases/releases/latest"><img src="https://img.shields.io/github/v/release/mouchard-app/releases?label=version&color=blue" alt="Latest version"></a>
  <img src="https://img.shields.io/badge/macOS-14%2B-lightgrey?logo=apple" alt="macOS 14 or later">
  <img src="https://img.shields.io/badge/status-private%20beta-orange" alt="Private beta">
  <a href="https://mouchard.app"><img src="https://img.shields.io/badge/website-mouchard.app-informational" alt="Website"></a>
</p>

<p align="center">
  <picture>
    <source srcset=".github/assets/main-dark.webp" media="(prefers-color-scheme: dark)">
    <img src=".github/assets/main-light.webp" width="800" alt="The Mouchard window: the sidebar with hosts and counters, the list of captured requests, and a JSON request and its response, decrypted.">
  </picture>
</p>

---

## Highlights

- 🔐 **HTTPS decryption**, with automatic detection of certificate pinning
- 📱 **iPhone and Xcode simulators**: install the certificate with a QR code or in one click
- 🔍 **Inspector** with colorized, foldable JSON, WebSockets, image and HTML previews
- 💡 **Clues** at a glance: JWTs decoded, redirects, CORS, cache, slow or large responses
- 🔁 **Replay** and **Edit and Replay** of any request
- 🧭 **Map Remote**, **Map Local**, **header rewriting** and **blocking**
- 📦 **HAR** import and export
- 🌍 English and French

## Install

1. Download [**Mouchard.dmg**](https://github.com/mouchard-app/releases/releases/latest/download/Mouchard.dmg).
2. Open it and drag **Mouchard** into **Applications**.
3. Launch it and enter your access code.

Mouchard keeps itself up to date: new versions are published here and installed through Sparkle, with their signature verified.

> [!NOTE]
> Mouchard is in **private beta**: the app asks for an access code on first launch.

## About this repository

This repository only hosts the release builds of Mouchard. Everything else is on **[mouchard.app](https://mouchard.app)**.
