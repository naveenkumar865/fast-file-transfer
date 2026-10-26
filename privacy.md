---
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy

**Publisher:** TADN Technology Limited
**App:** Fast File Transfer for Android, Android TV, Windows and Linux
**Effective date:** 25 October 2026

Fast File Transfer moves your files between your own devices, or between your device and a server you choose. It is built so that **we never receive your files or any information about you**. This policy explains exactly what the app does with data.

## The short version

- We **don't collect, store, sell or share** any personal data.
- The app has **no accounts, no ads, no analytics, no tracking and no crash reporting**.
- Files you send go **directly** to the device or server you choose, **end-to-end encrypted**. They never pass through servers run by TADN Technology Limited.

## What the app processes, and where it stays

| Data | What happens to it |
|---|---|
| **Files you send or receive** | Read from or saved to your device only when you start a transfer or accept an incoming one. Sent directly to the device or server you chose, encrypted on the way. We never receive them. |
| **Device name** (e.g. "Smart TV Pro") | While **Receive** is on, the app broadcasts this name and a device fingerprint on your **local network** so your other devices can find it. It is also shown to the device you transfer with. It never leaves your local network through us. You can change the name in the app. |
| **Device identity key and trusted devices** | A cryptographic key pair created on your device, and the list of devices you chose to trust. Stored only on your device and used to verify the devices you exchange files with. |
| **Server details** (SSH / SFTP) | The host names, user names and server fingerprints you connect to, kept on your device so you can reconnect. **Passwords and key passphrases are never stored.** |
| **Passphrases** (optional file encryption) | Used in memory to encrypt or decrypt your files, then discarded. Never stored or sent anywhere. |
| **Wi-Fi details** (band, link speed, network name) | Read on your device only, to suggest a faster 5 GHz connection. Never sent anywhere. |

The app's settings and keys are kept in its private storage and are excluded from cloud backups and device-to-device migration.

## Network connections the app makes

- **To devices on your local network**, while you send or receive files with them.
- **To the SSH/SFTP server you enter**, when you connect to it.
- **Name lookups (DNS):** when you connect to a server by name, the name is looked up through your network's DNS. On Android, if that is unavailable, the app asks a public resolver (Cloudflare `1.1.1.1` or Google `8.8.8.8`) to look up **that server name only**.

The app makes **no other connections**: it doesn't contact servers run by TADN Technology Limited or any third party.

## Permissions (Android)

| Permission | Why |
|---|---|
| Network and Wi-Fi state, multicast | To find your devices on the local network and transfer files to them; to show the Wi-Fi tip. |
| Storage / file access | To read the files you choose to send and save the files you accept. |
| Notifications and foreground service | To show a notification and keep a transfer, or **Receive** while you have it turned on, running when you switch to another app. You can stop it at any time with **Quit**. |

## App stores

If you install the app from **Google Play** or the **Microsoft Store**, the store handles the download and updates under its own privacy policy. We receive only the statistics those stores give every publisher, which don't identify you.

## Children

The app isn't directed at children and doesn't knowingly process children's personal data. In fact, it processes no personal data on our side at all.

## Security

Transfers between devices use a post-quantum hybrid key exchange (X25519 + ML-KEM-768) with AES-256-GCM or ChaCha20-Poly1305 encryption. Devices verify each other with a 6-digit code the first time, and each file is checked with SHA-256 before it is saved. SSH connections use only modern algorithms, with strict host-key checking.

## Changes

If this policy changes, the new version will be published at this address with a new effective date.

## Contact

TADN Technology Limited â€” **privacy@YOUR-DOMAIN**
