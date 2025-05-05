<h1 align="center">
🚀 Galxe Task Monitor Extension
</h1>

<p align="center">
<img src="./images/GalxeTaskMonitor.png" width="100%" alt="Galxe Task Monitor Banner" />
</p>

<p align="center">
A lightweight and privacy-focused Chrome Extension that notifies you about <b>new Galxe tasks</b> — ideal for <i>crypto airdrop hunters</i> who never want to miss a quest again.
</p>

<p align="center">
  <a href="#-features">Features</a> •
  <a href="#-installation">Installation</a> •
  <a href="#-setup-instructions">Setup</a> •
  <a href="#-privacy--security">Privacy</a> •
  <a href="#-how-it-works">How It Works</a> •
  <a href="#-faq">FAQ</a>
</p>

---

## 🧠 What It Does

A Chrome Extension that connects to Galxe's official GraphQL API to monitor selected projects (Spaces) and alerts users via browser notifications when new tasks are added.

---

## ✨ Features

<table>
  <tr>
    <td width="50%">
      <h3>🔍 Galxe API Integration</h3>
      <p>Connects directly to Galxe's GraphQL API to monitor quests in real-time</p>
    </td>
    <td width="50%">
      <h3>🎯 Targeted Project Tracking</h3>
      <p>You choose which <b>Galxe Spaces</b> (projects) to follow</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🔔 Browser Notifications</h3>
      <p>Alerts you the moment a new task is added</p>
    </td>
    <td width="50%">
      <h3>🧩 Badge Indicator</h3>
      <p>Displays "NEW" on the extension icon when updates are available</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🔐 Wallet-Free</h3>
      <p>No wallet connection required — 100% read-only</p>
    </td>
    <td width="50%">
      <h3>🔒 Secure & Private</h3>
      <p>API token stored locally. No data is sent to any server</p>
    </td>
  </tr>
</table>

---

## 🛠️ Installation

### 🌍 Chrome Web Store 

<p align="center">
  <a href="https://chromewebstore.google.com/detail/pkopghfmjolmobgbhiiopaojgojjpdfp?utm_source=item-share-cb">
    <img src="https://developer.chrome.com/static/docs/webstore/branding/image/iNEddTyWiMfLSwFD6qGq.png" alt="Available in the Chrome Web Store" width="250">
  </a>
</p>

> For the best experience and automatic updates, install the extension directly from the Chrome Web Store.
> 
> ⚠️ **Important**: This extension should only be installed from the official Chrome Web Store to ensure security and receive automatic updates.

### 🧪 Developer Installation (Manual- SOON )

1. Clone or download this repository
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable **Developer Mode** (toggle in top-right corner)
4. Click **Load unpacked**
5. Select the project root folder

---

## ⚙️ Setup Instructions

<details open>
<summary><b>1. Get Your Galxe API Token</b></summary>
<br>
<ul>
  <li>Log in to <a href="https://galxe.com">Galxe</a></li>
  <li>Go to your Account Settings</li>
  <li>Copy your <b>access-token</b></li>
</ul>
</details>

<details open>
<summary><b>2. Configure Extension</b></summary>
<br>
<ul>
  <li>Click the extension icon</li>
  <li>Open Settings</li>
  <li>Paste your token and save</li>
</ul>
</details>

<details open>
<summary><b>3. Add Projects (Spaces)</b></summary>
<br>
<ul>
  <li>Enter project aliases (e.g., <code>binance</code>, <code>layerzero</code>)</li>
  <li>Click <b>Add</b></li>
</ul>
</details>

That's it! The extension will check for new tasks every 5 minutes and notify you instantly.

---

## 🔐 Privacy & Security

<p align="center">
<img src="./images/GalxeTaskMonitorSecurity.png" width="100%" alt="Security and Privacy Focused" />
</p>

We take your security seriously:

<div align="center">
  <table>
    <tr>
      <td align="center">✅ No wallet connection</td>
      <td align="center">✅ No access to private keys</td>
    </tr>
    <tr>
      <td align="center">✅ No external tracking</td>
      <td align="center">✅ No data sent to our servers</td>
    </tr>
  </table>
</div>

<p align="center">
  <b>Everything is stored locally in your browser</b>
</p>

Only your Galxe `access-token` and project list are saved in `chrome.storage.local`.  
All interactions are made directly with the official Galxe API.

---

## 🧪 How It Works

<div align="center">
  <table>
    <tr>
      <td align="center">⏱️</td>
      <td>Polls Galxe every <b>5 minutes</b></td>
    </tr>
    <tr>
      <td align="center">🔍</td>
      <td>Tracks your selected projects for quest updates</td>
    </tr>
    <tr>
      <td align="center">🔄</td>
      <td>Checks task <code>credential.id</code> and <code>lastUpdate</code> timestamps</td>
    </tr>
    <tr>
      <td align="center">🔔</td>
      <td>Sends browser notifications and updates badge when new tasks are found</td>
    </tr>
  </table>
</div>

You can view updates by clicking the icon or notification, which opens the corresponding Galxe quest.

---

## 🧰 Developer Info

<div align="center">
  <table>
    <tr>
      <td align="center">💻</td>
      <td>GitHub (Main)</td>
      <td><a href="https://github.com/xPOURY4">@xPOURY4</a></td>
    </tr>
    <tr>
      <td align="center">🛠️</td>
      <td>GitHub (Team)</td>
      <td><a href="https://github.com/HexQuant-hub">HexQuant-hub</a></td>
    </tr>
    <tr>
      <td align="center">🐦</td>
      <td>Twitter</td>
      <td><a href="https://x.com/therealpourya">@therealpourya</a></td>
    </tr>
  </table>
</div>

---

## ❓ FAQ

<details>
<summary><b>Does this extension connect to my wallet?</b></summary>
<br>
No. It is 100% read-only and never asks for wallet access.
</details>

<details>
<summary><b>Where is my data stored?</b></summary>
<br>
In your browser's local storage — never sent to a server.
</details>

<details>
<summary><b>Can I use this on mobile?</b></summary>
<br>
No. Chrome Extensions currently only work on desktop browsers.
</details>

<details>
<summary><b>How often does it check for new tasks?</b></summary>
<br>
Every 5 minutes, which balances timely notifications with API rate limits.
</details>

---

## 📜 License

<p align="center">
This project is licensed under the <b>MIT License</b>.<br>
See <a href="./LICENSE">LICENSE</a> for details.
</p>

---

## 📄 Privacy Policy

<p align="center">
You can read the full privacy policy here:<br>
👉 <a href="./PRIVACY-POLICY.md">PRIVACY-POLICY.md</a>
</p>

---

## 🙏 Disclaimer

<p align="center">
This project is not affiliated with Galxe.<br>
It is an independent open-source tool developed by the community, for the community.
</p>

---

<p align="center">
<b>✨ Made with love by crypto builders ✨</b>
</p>
