# Linux Install Base Script

### Supported Systems
- [Ubuntu - 24.04 (Base)](https://ubuntu.com/download)

### Supported Architectures
- x86_64 (amd64)

<br/>

# Preparing to Run the Script

### Ubuntu
```bash
sudo apt install curl -y
```

<br/>

# Running the Script

### Ubuntu
```bash
curl -H 'Cache-Control: no-cache' -sSL https://raw.githubusercontent.com/daniloancilotto/linux-install-base-script/master/ubuntu.sh | bash
```

<br/>

# Installations and Configurations

### Ubuntu
- Kernel (Configuration Only)
  - Packages
    - Automatically Installed
  - Parameters
    - /etc/sysctl.d/60-swappiness.conf
    - /etc/sysctl.d/60-cache-pressure.conf
    - /etc/sysctl.d/60-inotify-watches.conf
- Wget - Latest (Repository)
- Tar - Latest (Repository)
- Zip - Latest (Repository)
- Rar - Latest (Repository)
- 7-Zip - Latest (Repository)
- Crudini - Latest (Repository)
- FFmpeg - Latest (Repository)
- Sensors - Latest (Repository)
- Samba - Latest (Repository)
- FUSE - Latest (Repository)
- OpenJDK - 8 (Repository)
  - Menu
    - ~/.local/share/applications/openjdk-8-policytool.desktop
- Htop - Latest (Repository)
  - Menu
    - ~/.local/share/applications/htop.desktop
- [4K Video Downloader - 4.33.5 (Dpkg)](https://www.4kdownload.com/downloads)
- [Angry IP Scanner - 3.9.1 (Dpkg)](https://angryip.org/download/)
- [Arduino IDE - 2.3.6 (AppImage)](https://www.arduino.cc/en/software/)
  - Menu
    - ~/.local/share/applications/arduino-ide.desktop
  - User Groups
    - dialout
- Audacity - Latest (Repository)
  - Menu
    - ~/.local/share/applications/audacity.desktop
- [balenaEtcher - 2.1.1 (AppImage)](https://etcher.balena.io)
  - Menu
    - ~/.local/share/applications/appimagekit-balena-etcher-electron.desktop
- DOSBox - Latest (Repository)
- [Dropbox - 2025.05.20 (Dpkg)](https://www.dropbox.com/install-linux)
- FileZilla - Latest (Repository)
  - Database
    - ~/.config/filezilla/queue.sqlite3
- Flameshot - Latest (Repository)
- [FreeRapid Downloader - 0.9u4 (Portable)](http://wordrider.net/freerapid/download.htm)
  - Menu
    - ~/.local/share/applications/freerapiddownloader.desktop
- GIMP - Latest (Repository)
- GNOME Calculator - Latest (Repository)
- [Google Chrome - Latest (Dpkg)](https://www.google.com/chrome/)
  - Menu
    - ~/.local/share/applications/google-chrome.desktop
- Kdenlive - Latest (Repository)
- LibreOffice - Latest (Repository)
  - Menu
    - ~/.local/share/applications/libreoffice-startcenter.desktop
- OBS Studio - Latest (Repository)
- Remmina - Latest (Repository)
  - Plugins
    - RDP
    - VNC
- [TeamViewer - Latest (Dpkg)](https://www.teamviewer.com/en-us/download/linux/)
- Transmission - Latest (Repository)
- [Ventoy - 1.1.05 (Portable)](https://www.ventoy.net/en/download.html)
  - Menu
    - ~/.local/share/applications/ventoy.desktop
- Virt-Manager - Latest (Repository)
  - Menu
    - ~/.local/share/applications/remote-viewer.desktop
- VLC - Lastest (Repository)
- [Zoiper5 - 5.6.9 (Dpkg)](https://www.zoiper.com/en/voip-softphone/download/current)
  - Autostart
    - ~/.config/autostart/Zoiper5.desktop
- Language Pack - Latest (Repository)
  - Languages
    - pt