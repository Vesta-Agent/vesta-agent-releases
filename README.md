<div align="center">

<img src="assets/logo.png" width="200" alt="Vesta Agent">

<a href="https://vesta-agent.github.io"><img src="https://img.shields.io/badge/Website-vesta--agent.github.io-6d5cff?style=for-the-badge" alt="Website"></a>

**[vesta-agent.github.io](https://vesta-agent.github.io)**

# Vesta Agent

**Your personal AI assistant — on your own device, in your own language**

[![Latest](https://img.shields.io/github/v/release/Vesta-Agent/vesta-agent-releases?color=3b82f6&style=for-the-badge)](https://github.com/Vesta-Agent/vesta-agent-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Vesta-Agent/vesta-agent-releases/total?color=7c3aed&style=for-the-badge)](https://github.com/Vesta-Agent/vesta-agent-releases/releases)
![Platforms](https://img.shields.io/badge/Windows%20%7C%20Android%20%7C%20Linux-0b1220?style=for-the-badge)

Made by **Persian Studio** · [**فارسی**](README.fa.md)

</div>

## Features

- **Smart agents** — mouse, commands, or both
- **Screen vision** and **voice calls**, only with your permission
- **Local-only memory** — no servers
- **Multiple API keys per agent** with automatic failover
- **Telegram** — bot or personal account, scheduled messages
- **Built-in proxy** with a step-by-step guide
- **Silent auto-update** · **9 languages** · **Safe review** before sensitive actions

## Download & install

### Windows 10 / 11
**[ VestaAgent-1.4.0-windows-x64-setup.exe](https://github.com/Vesta-Agent/vesta-agent-releases/releases/latest/download/VestaAgent-1.4.0-windows-x64-setup.exe)**
1. Run the installer.
2. On "Windows protected your PC", click **More info** > **Run anyway**.
3. Finish the setup.

### Windows 7 / 8
**[ VestaAgent-1.4.0-windows7-8-legacy-setup.exe](https://github.com/Vesta-Agent/vesta-agent-releases/releases/latest/download/VestaAgent-1.4.0-windows7-8-legacy-setup.exe)**
1. Run the installer; on SmartScreen click **More info** > **Run anyway**.
2. This build has no auto-update — download new versions here.

### Android
**[ VestaAgent-1.4.0-android.apk](https://github.com/Vesta-Agent/vesta-agent-releases/releases/latest/download/VestaAgent-1.4.0-android.apk)**
1. > Uninstall old **My Agent** versions below 1.2 first.
2. Open the APK and allow **Install unknown apps** when asked.
3. Tap **Install** (choose "Install anyway" if Play Protect warns).

### Linux
**deb:** [ VestaAgent-1.4.0-linux-amd64.deb](https://github.com/Vesta-Agent/vesta-agent-releases/releases/latest/download/VestaAgent-1.4.0-linux-amd64.deb)
```bash
sudo apt install ./VestaAgent-1.4.0-linux-amd64.deb
```
**AppImage:** [ VestaAgent-1.4.0-linux-x86_64.AppImage](https://github.com/Vesta-Agent/vesta-agent-releases/releases/latest/download/VestaAgent-1.4.0-linux-x86_64.AppImage)
```bash
chmod +x VestaAgent-1.4.0-linux-x86_64.AppImage && ./VestaAgent-1.4.0-linux-x86_64.AppImage
```

### VPS / server
> **Coming soon.** The server installer is being reworked and is currently disabled.

## First-run setup
1. Get a free key: [Google AI Studio](https://aistudio.google.com/apikey) or [OpenRouter](https://openrouter.ai/keys).
2. Paste it in **Settings > Keys** (add several for failover).
3. In Iran, set **Settings > Proxy** (e.g. `127.0.0.1:10808` from v2rayN/NekoBox) and press **Test**.

## FAQ
<details><summary>Where is my data stored?</summary>Only on your device. Only your prompts go to the AI provider whose key you added.</details>
<details><summary>Why does Windows warn me?</summary>The installer isn't commercially code-signed yet. Download only from this page and verify SHA256.</details>
<details><summary>1.3 doesn't auto-update?</summary>The update URL changed — install 1.4.0 manually once.</details>

## Verify (SHA256)
Download [SHA256SUMS](https://github.com/Vesta-Agent/vesta-agent-releases/releases/latest/download/SHA256SUMS), then: `sha256sum -c SHA256SUMS --ignore-missing` (Linux) or `Get-FileHash <file> -Algorithm SHA256` (Windows).

## Release notes
[All releases](https://github.com/Vesta-Agent/vesta-agent-releases/releases) · [v1.4.0](https://github.com/Vesta-Agent/vesta-agent-releases/releases/tag/v1.4.0)

<div align="center"><sub>© 2026 Persian Studio · This repository contains installers only.</sub></div>
