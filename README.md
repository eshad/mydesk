# MyDesk - P2P Remote Desktop

Cross-platform peer-to-peer remote desktop application. Connect to and control remote computers securely over the internet.

## Downloads

| Platform | File |
|----------|------|
| macOS | MyDesk-Installer-1.0.0.dmg |
| Windows | MyDesk_Setup_1.0.0.exe |

## Features

- Remote desktop streaming via WebRTC (60 fps, motion-optimized)
- Mouse & keyboard control with low-latency coalesced input
- Ctrl+Alt+Del to the remote Windows machine (real Secure Attention Sequence)
- Quality presets — Low / Balanced / High (adjustable bitrate & frame rate)
- Screenshot remote screen (saved to Downloads)
- Screen recording (saved as .webm to Downloads)
- In-session chat
- File transfer between devices (HTTP relay with resume)
- Clipboard sync (text and files)
- Password protection with remember device
- Auto-discovery of online devices
- Tabbed sessions (macOS)
- TURN TCP fallback for corporate firewalls
- Auto-connect and reconnect
- Launch at login

## Advanced / Admin Settings

Relay server configuration (IP and port) is protected and hidden from normal users.

- Open with **Ctrl+Shift+C**
- Enter the admin password to view or change the relay server (default: `P@ssw0rd`)
- The admin password can be changed from within the unlocked settings panel

## Required Ports (relay server)

TCP 3001, 3002, 3478 | UDP 3478, 49152-65535

(TCP 3478 is required for TURN over restrictive corporate firewalls.)

## License

MIT
