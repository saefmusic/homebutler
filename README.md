# 🏠 homebutler - Control Your Homelab From Chat

[![Download homebutler](https://img.shields.io/badge/Download-homebutler-brightgreen)](https://github.com/saefmusic/homebutler)

## 📋 What is homebutler?

homebutler helps you manage your home lab devices using chat commands. It runs as a single file and does not need anything else to work. You can control your devices easily without technical setup.  

The app works on Windows and lets you perform tasks like waking up your PC, checking your servers, or running simple commands remotely. It works by connecting your local devices through SSH and Wake-on-LAN technology.

homebutler is designed to be easy to use for everyone managing multiple devices at home or small offices.

---

## 🖥️ System Requirements

- Windows 10 or later (64-bit recommended)
- At least 100 MB free disk space
- Internet connection needed only for downloading and updates
- Local network access to your homelab devices (for SSH and Wake-on-LAN)

No special hardware or software is required. homebutler runs fast and uses minimal system resources.

---

## 🚀 Getting Started

1. Click the big download link at the top or visit the [official homebutler page](https://github.com/saefmusic/homebutler).  
2. Look for the latest Windows release file. It will usually be named like `homebutler-windows.exe` or similar.  
3. Click the file to download it to your computer.  
4. Once downloaded, find the file in your Downloads folder and double-click it to run.  
5. Windows may ask if you trust this file. Confirm that you want to run the app.  
6. homebutler will open a simple chat window where you can start typing commands.  

No installation process is needed. The app runs directly from the downloaded file.

---

## 💾 Download and Use homebutler on Windows

### Step 1: Download

You must first get the homebutler file from the official GitHub page below.  

[![Download homebutler](https://img.shields.io/badge/Download-homebutler-blue)](https://github.com/saefmusic/homebutler)

### Step 2: Run the App

- Find the downloaded file on your PC.
- Double-click the file. This opens the homebutler chat interface.
- If Windows security pops up, click “More info” then “Run anyway” to start.

### Step 3: Set Up Connection to Your Devices

Before using advanced commands, make sure your homelab devices:

- Allow SSH connections (you may need to enable SSH on devices like Raspberry Pi or servers).
- Support Wake-on-LAN (usually in BIOS or system settings).

You will need to know your device IP addresses and user credentials for SSH.

---

## 🛠️ How to Use homebutler

homebutler uses simple text commands inside the chat interface. Here are some common commands to try:

- `wake pc1` - Sends a Wake-on-LAN signal to turn on your first computer.
- `ssh status server1` - Checks if your server is reachable over SSH.
- `check disk pi` - Gets disk space information from your Raspberry Pi device.
- `restart server2` - Restarts a connected server remotely.
- `help` - Shows a list of available commands.

Commands are plain text and designed to be easy to remember.

---

## 🔧 Configuring Your Devices

To make homebutler work fully, you need to add your device details:

1. Open the settings menu in homebutler (type `settings`).
2. Add your device’s IP address, SSH username, and password or key.
3. Save the device profile.
4. Use the device name to run commands, such as `wake` or `ssh status`.

You can add several devices and manage them all from one place.

---

## 🖥️ Managing Raspberry Pi with homebutler

If you use Raspberry Pi devices:

- Ensure SSH is enabled in Raspberry Pi settings.
- Find the Pi’s IP address by running `hostname -I` on the device.
- Add the Pi to homebutler settings with this IP and SSH credentials.
- Run commands like `check cpu pi` or `restart pi`.

This makes it easy to monitor your Pi without needing to log in manually.

---

## 🔌 Wake-on-LAN Support

homebutler can turn on your computers remotely using Wake-on-LAN (WOL).

To use WOL:

- Enable Wake-on-LAN in your device BIOS or UEFI.
- Connect homebutler to the device’s MAC address.
- Use the `wake` command with the device name.

This is helpful if your device is powered off but still has power to the network card.

---

## 📡 Networking Setup Tips

For homebutler to connect correctly:

- Your Windows PC and homelab devices must be on the same local network.
- Your devices should have static IP addresses or reserved DHCP addresses to avoid changes.
- SSH ports (usually 22) must be open on the devices.
- Wake-on-LAN packets rely on broadcast message capability in your network.

---

## ⚙️ Troubleshooting

- **App does not open:** Make sure you downloaded the Windows file and run as administrator if needed.
- **Cannot connect to device via SSH:** Verify IP address, username, and password or SSH keys.
- **Wake-on-LAN not working:** Check BIOS settings and network configuration for your device.
- **Commands do not respond:** Confirm the device is online and reachable on the network.

For frequent problems, restart homebutler and your devices.

---

## 🔒 Security Considerations

Keep your SSH credentials safe. Only run homebutler files downloaded from the official GitHub page. Avoid sharing sensitive information in public chat environments.

---

## 📚 More Info and Updates

You can always get the latest version and find help on the official page:

[https://github.com/saefmusic/homebutler](https://github.com/saefmusic/homebutler)