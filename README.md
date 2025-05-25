
<p align="center">
  <img src="https://raw.githubusercontent.com/UpdateXLeaks/say-gex/main/.github/assets/macbruh-logo.png" alt="MACBRUH-RDP" width="180"/>
</p>

<h1 align="center">🖥️ MACBRUH-RDP</h1>
<h3 align="center">Your Next-Level Cloud Windows RDP Automation with Audio & Power 🚀</h3>

<p align="center">
  <a href="https://github.com/UpdateXLeaks/say-gex/actions">
    <img alt="GitHub Actions" src="https://img.shields.io/github/actions/workflow/status/UpdateXLeaks/say-gex/macbruh-rdp.yml?branch=main">
  </a>
  <a href="https://github.com/UpdateXLeaks/say-gex/stargazers">
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/UpdateXLeaks/say-gex?style=social">
  </a>
  <a href="https://github.com/UpdateXLeaks/say-gex/blob/main/LICENSE">
    <img alt="License" src="https://img.shields.io/github/license/UpdateXLeaks/say-gex">
  </a>
</p>

---

## ✨ Features

- **Remote Desktop (Chrome Remote Desktop) Ready**
- **Full Audio Support** (VB-Cable virtual audio + Windows Audio service)
- **User-Selectable Software** (via Chocolatey)
- **Long-Running Sessions** (up to 30 days 🕒)
- **System Diagnostics & Monitoring**
- **Modern Logging & Workflow Summaries**
- **Easy Desktop Shortcuts**
- **Discord Notification Support**
- **Beautifully Documented & Clean Automation**

---

## 🚀 Quick Start

1. **Fork or Clone this Repository**
2. **Configure your Workflow:**

   - Go to `.github/workflows/macbruh-rdp.yml`
   - (Optional) Add your Discord webhook in repo secrets as `DISCORD_WEBHOOK`.

3. **Run the Workflow:**
   - Go to the **Actions** tab.
   - Select **MACBRUH-RDP** workflow.
   - Click **Run workflow**, fill in required options, and launch!

---

## 🛡️ Security & Compliance Notice

> **Warning:**  
> This project is for educational, research, and private self-hosted runner use only.  
> Running RDP/audio on public GitHub-hosted runners is against GitHub Actions TOS.

---

## 💡 Inputs & Customization

| Input Name         | Required | Description                                                | Example                        |
|--------------------|----------|------------------------------------------------------------|--------------------------------|
| `code`             | ✅       | Chrome Remote Desktop Auth Code                            | `XXXX-XXXX-XXXX`               |
| `extra_packages`   | ❌       | Additional Chocolatey packages (comma separated)           | `git,python,vscode`            |
| `keep_alive_minutes`| ❌      | Session duration (10-43800, default 60 minutes)            | `180`                          |

---

## 🎧 Audio Support

- **Windows Audio Service** auto-enabled
- **VB-Cable** virtual driver installed for full audio routing
- **FFmpeg & VLC** for advanced audio/video manipulation

---

## 🛠️ Software & Tools

- Chrome
- Chrome Remote Desktop
- 7zip
- VLC Media Player
- FFmpeg
- **And any extra packages you specify!**

---

## 📊 System Diagnostics

- System information and top processes are saved and uploaded as workflow artifacts for every session.

---

## 📚 Example: Running MACBRUH-RDP

```bash
# 1. Fork or clone the repo
git clone https://github.com/UpdateXLeaks/say-gex.git

# 2. (Optional) Add your Discord webhook as a repository secret: DISCORD_WEBHOOK

# 3. Go to GitHub Actions tab, select MACBRUH-RDP, and run with your parameters!
