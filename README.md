# 🛠️ ToolBox Activator

### 🎯 The All-in-One Automation for JetBrains IDE Activation

**Effortless, cross-platform activation for the entire JetBrains suite powered by ja-netfilter.**

---

```ascii
JJJJJJ   EEEEEEE   TTTTTTTT  BBBBBBB    RRRRRR    AAAAAA    IIIIIIII  NNNN    NN   SSSSSS
   JJ    EE           TT     BB    BB   RR   RR   AA  AA        II      NNNNN   NN  SS
   JJ    EE           TT     BB    BB   RR   RR   AA  AA        II      NN NNN  NN   SS
   JJ    EEEEE        TT     BBBBBBB    RRRRRR    AAAAAA        II      NN  NNNNN    SSSSS
   JJ    EE           TT     BB    BB   RR   RR   AA  AA        II      NN   NNNN        SS
JJ JJ    EE           TT     BB    BB   RR   RR   AA  AA        II      NN    NNN        SS
 JJJJ    EEEEEEE      TT     BBBBBBB    RR   RR   AA  AA    IIIIIIII  NN     NNN   SSSSSS

```

## 📝 Overview

**ToolBox Activator** is a streamlined automation utility designed to configure and activate all installed JetBrains IDEs. By automating the deployment of `ja-netfilter`, managing `.vmoptions`, and generating license keys, it removes the manual overhead of setting up your development environment on **Windows, macOS, and Linux**.

---

## ✨ Key Features

* 🚀 **One-Click Execution** – Activate your entire JetBrains toolbox with a single command.
* 🔄 **Smart Detection** – Automatically scans your system to identify all installed IDEs.
* 🌐 **Universal Compatibility** – Native support for Windows (PowerShell), macOS, and Linux (Bash/Zsh).
* 📦 **Auto-Dependency Management** – Automatically fetches required tools like `curl` and `jq`.
* 🧹 **System Cleanup** – Clears remnants of previous activators to ensure a clean state.
* 💾 **Safe Modification** – Automatically creates backups of configuration files before any changes.
* 🛡️ **Integrity Checks** – Uses SHA-1 hash verification for all downloaded components.

---

## 💻 Supported IDEs

| IDE | Edition / Description | Status |
| --- | --- | --- |
| 🎨 **IntelliJ IDEA** | Ultimate & Community | ✅ Full |
| ⚙️ **CLion** | C/C++ IDE | ✅ Full |
| 🐘 **PhpStorm** | PHP IDE | ✅ Full |
| 🎯 **GoLand** | Go IDE | ✅ Full |
| 🐍 **PyCharm** | Python IDE | ✅ Full |
| 🌐 **WebStorm** | Web Frontend IDE | ✅ Full |
| 🎮 **Rider** | .NET IDE | ✅ Full |
| 🗄️ **DataGrip** | SQL IDE | ✅ Full |
| 🦀 **RustRover** | Rust IDE | ✅ Full |

---

## 🛠️ Installation and Usage

### 🚀 Quick Start

#### **Windows (PowerShell)**

```powershell
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/neKamita/toolbox-activator/main/activate.ps1" -OutFile "activate.ps1"
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
.\activate.ps1

```

#### **macOS / Linux (Bash)**

```bash
curl -o activate.sh https://raw.githubusercontent.com/neKamita/toolbox-activator/main/activate.sh
chmod +x activate.sh
./activate.sh

```

---

## ⚠️ Troubleshooting

| Issue | Potential Solution |
| --- | --- |
| **"No IDEs Found"** | Run the IDE at least once so it generates its local config folders. |
| **Permission Denied** | On Linux/macOS, use `sudo`. On Windows, run PowerShell as Admin. |
| **Key is Invalid** | Ensure the IDE was **fully closed** during the script execution. |

---

## 🙏 Credits & Sources

This project is an automation wrapper that relies on the amazing work of the following communities:

* **[ja-netfilter](https://www.google.com/search?q=https://github.com/ja-netfilter/ja-netfilter)** — The core plugin technology that enables the activation process.
* **[ckey.run](https://ckey.run)** — The primary source for license generation scripts and updated filters.

---

## 🔐 Security & License

* **MIT License**: Free to use, modify, and distribute.
* **Privacy**: All license generation is performed **locally** on your machine.

> [!WARNING]
> This tool is intended for educational and testing purposes. The author is not responsible for any misuse or potential license blacklisting by the software vendor. Use at your own risk.

---

<div align="center">

**Found this helpful? Give us a ⭐ on GitHub!**

Made with ❤️ by [neKamita](https://github.com/neKamita)


[Repository](https://github.com/neKamita/ToolBox-Activator)


Direct Add for Keys : [key site](https://ckey.run/)


</div>
