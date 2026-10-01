# 🛡️ OGHYANOS VPN

<p align="center">
  <img src="path/to/your/logo.png" alt="OGHYANOS VPN Logo" width="150" height="150">
</p>

<p align="center">
  <b>A modern, secure, and easy-to-use VPN client for Windows.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows-blue" alt="Platform">
  <img src="https://img.shields.io/badge/License-Proprietary-red" alt="License">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen" alt="Status">
</p>

---

## 📖 Overview

**OGHYANOS VPN** is a powerful and lightweight VPN client designed for Windows users who value privacy, speed, and simplicity. Built with a modern architecture, it provides a seamless and secure way to protect your internet connection.

This application is **proprietary software** and is distributed as a standalone installer. The source code is not publicly available. To use the application, simply download the latest release from the official GitHub repository and run the installer.

---

## ✨ Key Features

- **🚀 Modern & Intuitive UI:** A sleek, dark-themed, and responsive interface that is easy to navigate.
- **🛡️ Secure TUN Mode:** Routes all your system traffic through an encrypted tunnel using state-of-the-art protocols.
- **🔌 VLESS & OpenVPN Support:** Connects to servers using VLESS (WebSocket + TLS) or traditional OpenVPN configurations.
- **🔄 Automatic Updates:** The built-in auto-updater checks for new versions and notifies you when an update is available, ensuring you always have the latest features and security patches.
- **🌐 Customizable DNS:** Configure Direct DNS (for domestic traffic) and Tunnel DNS (for encrypted DNS queries inside the tunnel) directly from the settings menu.
- **🔒 Administrator Privilege Elevation:** Automatically requests the necessary permissions to create the TUN interface for a secure connection.
- **🧹 Clean Disconnection:** Utilizes Windows Job Objects to guarantee that all related processes are terminated when the application is closed, leaving no background tasks running.
- **📊 Real-time Status:** Provides clear visual feedback on your connection status and simulated download/upload speeds.

---

## 💻 System Requirements

- **Operating System:** Windows 10 or Windows 11 (64-bit).
- **Administrator Privileges:** Required for TUN mode.
- **Internet Connection:** Required for downloading the installer and connecting to VPN servers.
- **OpenVPN:** (Optional) If you plan to use OpenVPN connections, you need to have OpenVPN Community 2.6+ installed. This is not required for VLESS connections.

---

## 📥 Installation Guide

Installing OGHYANOS VPN is quick and simple. Follow these steps:

1.  **Download the Latest Release:**
    Go to the official releases page and download the latest setup file:
    
    **[➡️ Download Latest Version](https://github.com/Oghyanos-App/Oghyanos-App/releases)**

2.  **Run the Installer:**
    Locate the downloaded `.exe` setup file and double-click it to run the installer.

3.  **Follow the Setup Wizard:**
    Follow the on-screen instructions in the setup wizard to complete the installation.

4.  **Launch the Application:**
    Once installed, launch OGHYANOS VPN from your desktop or Start Menu.

5.  **Grant Administrator Privileges:**
    When prompted by Windows User Account Control (UAC), click **Yes** to allow the application to run with Administrator privileges. This is essential for creating the TUN interface.

---

## 🚀 How to Use

1.  **Select a Server:**
    Click on the server selector at the bottom of the main screen to choose from available locations.

2.  **Connect:**
    Click the large power button in the center of the screen to connect. The button will change color and the status will update to "Protected".

3.  **Disconnect:**
    Click the power button again to disconnect. The status will return to "Disconnected".

4.  **Configure DNS (Optional):**
    Click the settings gear icon in the top-right corner, then select **Settings**. Here you can configure your Direct and Tunnel DNS preferences.

5.  **Check for Updates:**
    From the settings menu, you can also click **Check for Updates** to manually look for new versions.

---

## 🔄 Auto-Updater

OGHYANOS VPN includes a built-in auto-updater that works as follows:

1.  **Automatic Check:** When the application starts, it automatically checks for updates in the background.
2.  **Update Notification:** If a new version is available, a banner will appear at the top of the screen.
3.  **Download:** Click the button on the banner to download the update.
4.  **Install & Restart:** Once the download is complete, the button will change to "Restart & Update". Clicking it will close the application, install the new version, and restart the app automatically.

---

## ❓ Frequently Asked Questions (FAQ)

**Q: Is OGHYANOS VPN open-source?**
A: No, this is proprietary software. The source code is not publicly available. You can only download the compiled installer from the official releases page.

**Q: Do I need to install OpenVPN separately?**
A: Only if you plan to use OpenVPN connections. For VLESS connections, which are the default, you do not need to install OpenVPN.

**Q: The application is asking for Administrator privileges. Is this safe?**
A: Yes, this is completely safe. Administrator privileges are required to create the TUN network interface, which is necessary for routing all your traffic through the VPN tunnel securely.

**Q: How do I uninstall the application?**
A: You can uninstall OGHYANOS VPN like any other Windows application via **Settings > Apps > Installed Apps** or the **Control Panel > Programs and Features**.

---

## ⚠️ Disclaimer

This application is provided for educational and personal use only. The developers are not responsible for any misuse or legal consequences. Please ensure you comply with your local laws regarding VPN usage.

---

## 📄 License

This project is proprietary software. All rights reserved. Unauthorized distribution or modification is strictly prohibited.
