# LaraCast releases

Windows installers for **LaraCast** by LaraDev: mirror your iPhone (AirPlay)
or Android phone to your PC and record it over a background, with AI noise suppression.

**Download:** the latest `LaraCast-Setup-<version>.exe` from [Releases](../../releases/latest).
Installed apps update themselves.

- Windows 10/11, 64-bit. Installs for your user, no admin needed.
- iPhone: open Control Center → Screen Mirroring → choose your PC. If it doesn't show up, click
  **Fix network** in the app once.
- Android 11+: pair once over Wireless debugging (steps in the app).

Betas are marked *Pre-release*; the app offers them only with **Settings → Get beta updates**.

Each release lists its SHA-256 checksums in `SHA256SUMS.txt`.

## Open-source components

LaraCast includes [UxPlay](https://github.com/FDH2/UxPlay) (GPL-3.0): each release names the UxPlay
commit it was built from and attaches LaraCast's patch (`uxplay-laracast.patch`). It also bundles
[scrcpy](https://github.com/Genymobile/scrcpy) (Apache-2.0), FFmpeg and GStreamer (LGPL/GPL),
[DeepFilterNet](https://github.com/Rikorose/DeepFilterNet) (MIT/Apache-2.0),
[DPDFNet](https://github.com/ceva-ip/DPDFNet) (Apache-2.0) and
[GTCRN](https://github.com/Xiaobin-Rong/gtcrn) via
[web-noise-suppressor](https://github.com/sapphi-red/web-noise-suppressor) (MIT).
