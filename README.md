# EPA Cockpit

A desktop app for [EPA Carriers](https://epacarriers.agency). It opens the same site in its own window, keeps you signed in, and works on Windows, Mac, and Linux.

**You need an internet connection.** This app shows the live EPA Cockpit website.

---

## Download

Click the file for your computer. No technical setup is required.

| Your computer | Download this | Then do this |
|---|---|---|
| **Windows 10 or 11** | [EPA-Cockpit-Setup-1.0.0.exe](https://github.com/bateesatobi/EPA-Cockpit/releases/latest/download/EPA-Cockpit-Setup-1.0.0.exe) | Double-click the file and follow **Next** until it finishes. Open **EPA Cockpit** from the desktop or the Start menu. |
| **Mac** | [EPA-Cockpit-1.0.0-mac-x64.dmg](https://github.com/bateesatobi/EPA-Cockpit/releases/latest/download/EPA-Cockpit-1.0.0-mac-x64.dmg) | Open the file, drag **EPA Cockpit** into **Applications**, then open it from there. |
| **Linux (Ubuntu / Debian)** | [EPA-Cockpit-1.0.0-linux-amd64.deb](https://github.com/bateesatobi/EPA-Cockpit/releases/latest/download/EPA-Cockpit-1.0.0-linux-amd64.deb) | Double-click the file (or run `sudo dpkg -i EPA-Cockpit-1.0.0-linux-amd64.deb`). |
| **Linux (any distro)** | [EPA-Cockpit-1.0.0-linux-x86_64.AppImage](https://github.com/bateesatobi/EPA-Cockpit/releases/latest/download/EPA-Cockpit-1.0.0-linux-x86_64.AppImage) | Right-click the file → **Properties** → allow running as a program, then double-click it. |

All files are also on the **[Releases page](https://github.com/bateesatobi/EPA-Cockpit/releases/latest)**.

### If Windows blocks the installer

Windows may say the app is unrecognized (it is not yet signed by Microsoft).

1. Click **More info**
2. Click **Run anyway**

### If a Mac says the app can’t be opened

1. Find **EPA Cockpit** in Applications
2. **Right-click** it (or Control-click)
3. Choose **Open**, then **Open** again

### Extra Windows option (no installer)

If you cannot run the setup file, download [EPA-Cockpit-1.0.0-win-x64.zip](https://github.com/bateesatobi/EPA-Cockpit/releases/latest/download/EPA-Cockpit-1.0.0-win-x64.zip), unzip it, and double-click **EPA Cockpit.exe**.

---

## What you get

- The EPA Cockpit site in a normal app window
- Your login stays saved between launches
- Links to other websites or email open in your usual browser

This is a desktop wrapper for https://epacarriers.agency. It is not an iPhone/iPad app.

---

## For developers

```bash
git clone https://github.com/bateesatobi/EPA-Cockpit.git
cd EPA-Cockpit
npm install
npm start
```

Build installers:

```bash
npm run dist        # Windows + macOS + Linux
npm run dist:win
npm run dist:mac
npm run dist:linux
```

Output goes to `dist/`.
