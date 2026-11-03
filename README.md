<div align="center">

# Metaforce Releases

### The Native Desktop Suite for Salesforce Professionals

Multi-org connection manager, pre-flight diff deployments, advanced SOQL worksheets, and local SFDX workflows — all in one unified, high-performance desktop application.

[![Latest Release](https://img.shields.io/github/v/release/Metaforce-Awesome/releases?color=0066ff&label=latest%20version)](https://github.com/Metaforce-Awesome/releases/releases/latest)
[![Platform - macOS](https://img.shields.io/badge/Platform-macOS-lightgrey?logo=apple&logoColor=black)](https://github.com/Metaforce-Awesome/releases/releases/latest)
[![Platform - Windows](https://img.shields.io/badge/Platform-Windows-blue?logo=windows&logoColor=white)](https://github.com/Metaforce-Awesome/releases/releases/latest)
[![Official Website](https://img.shields.io/badge/Website-metaforce.ltd-0066ff)](https://metaforce.ltd)
[![Docs](https://img.shields.io/badge/Docs-User%20Guide-blueviolet)](https://metaforce.ltd/user-guide)

[**Official Website**](https://metaforce.ltd) • [**Documentation**](https://metaforce.ltd/user-guide) • [**Changelog**](https://github.com/Metaforce-Awesome/releases/releases) • [**Report an Issue**](https://github.com/Metaforce-Awesome/releases/issues)

</div>

---

## 📦 Official Downloads

This repository hosts official release binaries, automatic update packages, and changelogs for Metaforce desktop releases.

| Operating System | Architecture | Package Format | Direct Download |
| :--- | :--- | :--- | :--- |
| **macOS** | Apple Silicon (M1 / M2 / M3 / M4) | `.dmg` | [**Download Metaforce-arm64-mac.dmg**](https://github.com/Metaforce-Awesome/releases/releases/latest/download/Metaforce-arm64-mac.dmg) |
| **Windows** | Windows 10 / 11 (64-bit) | `.exe` Setup | [**Download Metaforce-x64-win.exe**](https://github.com/Metaforce-Awesome/releases/releases/latest/download/Metaforce-x64-win.exe) |

> 💡 **Need previous releases or detailed release notes?**  
> Browse all standalone builds, historical tags, and checksums in the [**Releases Archive**](https://github.com/Metaforce-Awesome/releases/releases).

---

## 🛡️ Security & Privacy Architecture

Metaforce is built from the ground up for enterprise compliance, confidentiality, and performance:

* 🔒 **Direct Local Execution**: Your machine communicates directly with official Salesforce API endpoints (`login.salesforce.com`, `test.salesforce.com`, or custom My Domains). **No intermediary proxy or third-party servers.**
* 🔑 **Official OAuth 2.0**: Metaforce never touches or stores your Salesforce user passwords. All authorizations utilize Salesforce-approved OAuth 2.0 PKCE web-server flows.
* 💾 **Encrypted Local Storage**: Session tokens and project workspace configurations are encrypted locally on your operating system's keychain/secure store.
* 🛡️ **Zero Telemetry on Data**: Queries, schemas, Apex code, and business data are processed in local volatile memory and never transmitted outside your authorized Salesforce tenant.

---

## ⚙️ Installation & Security Prompts

Metaforce is an independently distributed tool for developer and admin productivity. Because releases are distributed directly via GitHub without commercial code-signing certificate overheads, your operating system or browser may show standard unrecognized app prompts. **All official packages distributed here are 100% clean, malware-free, and safe to execute.**

<details>
<summary><b>▶ Windows Installation Guide (SmartScreen / Browser Warning)</b></summary>

### 1. Browser Download Notice (Edge / Chrome)
When downloading `.exe` files, your browser may report that the file *"isn't commonly downloaded"*:
1. Hover over the download card in your browser download shelf and click **`...`** (More actions).
2. Choose **Keep** (保留).
3. Click **Show more** and select **Keep anyway** (仍要保留).

### 2. Windows Defender SmartScreen ("Windows protected your PC")
1. On the blue SmartScreen dialog, click the underlined link: **"More info"** (*更多信息*).
2. Click the **"Run anyway"** (*仍要运行*) button to launch the setup wizard.
</details>

<details>
<summary><b>▶ macOS Installation Guide ("Unidentified Developer")</b></summary>

If macOS displays a warning that the application cannot be opened because it is from an unidentified developer:
1. Open your `Applications` folder in Finder.
2. **Right-click** (or <kbd>Control</kbd>-click) `Metaforce.app`.
3. Select **Open** from the context menu, then click **Open** in the confirmation dialog.
4. Subsequent launches will open instantly without prompts.
</details>

---

## ✨ Key Capabilities

* 🚀 **1-Click Passwordless Switch**: Connect all your Production, Sandbox, and Scratch orgs once. Switch between them instantly without 2FA or credential fatigue.
* 🔍 **Pre-Flight Diff Deploy**: Side-by-side diff between source and target org before shipping metadata. Validate test runs with zero overwrite risk.
* 📊 **SOQL Explorer & Data Movement**: Multi-tab SQL/SOQL console with auto-completion, field inspection, and Bulk API 2.0 export/import.
* 🌿 **Flow & Automation Organizer**: Group flows by standard/custom objects with visual version comparison and active trigger status.
* 🛠️ **Native SFDX Support**: Seamlessly sync and deploy local SFDX project files with split-screen code editing.

---

## 🔍 Package Verification (SHA-256)

For security verification, every official release published on GitHub includes SHA-256 checksums in the release notes.

To verify your downloaded package locally:

**macOS**:
```bash
shasum -a 256 Metaforce-arm64-mac.dmg
```

**Windows (PowerShell)**:
```powershell
Get-FileHash .\Metaforce-x64-win.exe -Algorithm SHA256
```

---

## 💬 Support & Inquiries

* 📖 **Documentation**: [https://metaforce.ltd/user-guide](https://metaforce.ltd/user-guide)
* 🐛 **Report a Bug / Request a Feature**: [GitHub Issues](https://github.com/Metaforce-Awesome/releases/issues)
* 🌐 **Website**: [https://metaforce.ltd](https://metaforce.ltd)
* ✉️ **Contact Support**: support@metaforce.ltd

<div align="center">
<sub>© Metaforce. Salesforce, Sales Cloud, and Service Cloud are trademarks of Salesforce, Inc.</sub>
</div>
