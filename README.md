# Duet — downloads

Public download mirror for **Duet**, an offline, end-to-end-encrypted
device-to-device file transfer app. No account, no cloud, no tracking.

- **Website:** https://duet-file-share.web.app
- **Android:** [Google Play](https://play.google.com/store/apps/details?id=com.majskquare.filesharer)
- **iOS:** coming soon
- **Source:** kept private — this repo holds release binaries only.

## Windows (beta)

**[⬇ Download Duet for Windows (x64) — latest](https://github.com/michal-giza/duet-downloads/releases/latest/download/duet-windows-x64.zip)**

1. Unzip anywhere (keep all files together).
2. Run **Duet.exe**.
3. On "Windows protected your PC" → **More info → Run anyway** (this build isn't code-signed yet).
4. On the first transfer, allow the Windows Defender Firewall prompt on **Private** networks.

Requires **Windows 11** (the secure transfer uses ChaCha20-Poly1305). If the app
won't start, install the
[Microsoft Visual C++ Redistributable (x64)](https://aka.ms/vs/17/release/vc_redist.x64.exe).

To receive a file from your phone: open Duet → **Receive** → scan the on-screen
QR code with Duet on your phone, on the same Wi-Fi/LAN.
