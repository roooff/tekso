# Install TEKSO

[Български](bg/install.md) · [Docs index](README.md)

TEKSO 0.9.1 Preview runs on macOS 12 or later (Apple Silicon; an Intel build is not available yet) and Windows 10 or later (64-bit).

## 1. Download

1. Open the **Releases** page of this repository.
2. Download the installer for your system and the checksum (SHA-256) published with the same release.

Download only from the **Releases** page of this repository.

## 2. Verify the download

Compare the SHA-256 of your file with the published value. If they differ, delete the file and download again.

**macOS** (Terminal):

```
shasum -a 256 ~/Downloads/<file-name>
```

**Windows** (PowerShell):

```
Get-FileHash $env:USERPROFILE\Downloads\<file-name> -Algorithm SHA256
```

## 3. Install

**macOS:** open the downloaded `.dmg` file and drag **TEKSO** into the **Applications** folder in the window that opens. Then eject the disk image.

**Windows:** two installers are offered.

- The **.exe** installer installs for your user only. It does not need administrator rights.

## 4. First launch of an unsigned app

The beta installers are not code-signed, so your system asks once.

**macOS**

1. Open TEKSO. When macOS says it cannot verify the developer, click **Done**.
2. Open **System Settings → Privacy & Security**.
3. Scroll down and click **Open Anyway** next to TEKSO.
4. Confirm once more. From then on it opens normally.

**Windows**

1. When the blue **Windows protected your PC** window appears, click **More info**.
2. Click **Run anyway**.

## 5. License agreement

On first start TEKSO shows a short license agreement. Click **I agree** to continue, or **Quit** to close the app. The full text is in [EULA.md](../EULA.md).

## Update

At start TEKSO checks GitHub for a newer version (see [Privacy](privacy.md#what-leaves-your-computer); you can turn this off). If there is one, it is downloaded in the background and a small panel offers **Restart and install**. Nothing is installed until you click it, and unsaved documents must be saved first. You can also choose **Check for updates** in the menu.

The downloaded package is checked against TEKSO's update signature before it is installed. This signature is not an Apple or Microsoft code signature: the app is still unsigned in their sense.

- **macOS:** TEKSO can only update itself when it runs from a normal folder such as **Applications**. If it runs from the disk image or macOS runs it from a temporary copy, move it to **Applications** with Finder and open it again.
- **Windows:** the installer runs with a progress bar and reopens TEKSO. Windows may ask again whether to run an unrecognised app.

TEKSO 0.9.0 beta 1 and beta 2 have no updater: update them once by hand. To update by hand at any time, download the new version from **Releases**, verify it and install it over the old one. Your files and settings are kept.

## Uninstall

- **Windows:** open **Settings → Apps**, find TEKSO and uninstall it.
- **macOS:** quit TEKSO and move it from **Applications** to the Trash.

Uninstalling does not delete your documents or the TEKSO data folder. To remove that too, see [Privacy](privacy.md#delete-your-data).
