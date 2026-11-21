# Vision Server

**EN.** A background add-on for [Vision for Windows](https://github.com/drugoj00/vision-for-windows). Your PC serves torrents over the local network, and Vision for Android connects to it with **Settings > Engine > External server**.

- Address, access key and QR code on the **Server** page of Vision for Windows
- Start, stop, port, network access, start with Windows
- Clients and request log
- Runs in the background without a window, works with the same protocol as the Android client expects
- Russian, Ukrainian, English

**Install:** in Vision for Windows open **Server** and press **Install**. The program picks the file for your Windows by itself and checks its SHA-256. Without internet use **Install from a file** with the zip from the [Releases](https://github.com/drugoj00/vision-server/releases/latest) page.

| File | Windows | Engine |
|---|---|---|
| `Vision-Server-1.0-win-x64.zip` | 64-bit | classic and fast |
| `Vision-Server-1.0-win-x86.zip` | 32-bit | classic and fast |
| `Vision-Server-1.0-win-arm64.zip` | ARM64 | fast (Go) only |

The ARM64 build has no classic (libtorrent) engine, because libtorrent has no Windows ARM64 build: it plays torrents with the fast Go engine, without full downloads to disk.

Checksums: `SHA256.txt` in every release.

Vision Server is a separate download. Vision for Windows does not need it to play or download.

**Requirements:** Windows 10 or newer, Vision for Windows. Allow the program in the firewall once (button on the Server page).

**Support:** [Telegram channel](https://t.me/PhoneInWindowSound), [all our programs](https://drugoj00.github.io/).

If the add-on is useful, please star the repository.

## License

Proprietary license, see [LICENSE](LICENSE): all rights reserved; free for personal use, no ads; redistribution only in the original unmodified form with the author named. Third-party components keep their own licenses: libtorrent (BSD-3-Clause), anacrolix/torrent (MPL-2.0).

The program contains and provides no content. You are responsible for what you open.
