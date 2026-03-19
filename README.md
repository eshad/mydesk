# MyDesk - P2P Remote Desktop

Cross-platform peer-to-peer remote desktop application. Connect to and control remote computers securely over the internet.

## Downloads

| Platform | File |
|----------|------|
| macOS | MyDesk-Installer-1.0.0.dmg |
| Windows | MyDesk_Setup_1.0.0.exe |

## Features

- Remote desktop streaming via WebRTC
- Mouse & keyboard control
- File transfer between devices
- Password protection with remember device
- Auto-discovery of online devices
- Tabbed sessions (macOS)
- TURN TCP fallback for corporate firewalls
- Auto-connect and reconnect
- Launch at login

## Server Setup

```bash
cd signaling-server
./deploy.sh user@your-server.com your-key.pem
```

Required ports: TCP 3001, 3002, 3478 | UDP 3478, 49152-65535

## License

MIT
