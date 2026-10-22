# Tombstone of Elysium

Release binaries of the **Tombstone of Elysium (ToE) storage node** (`toed`) for Linux. This repository contains **no source code**.

- The node is free. It is only useful together with the ToE app (Apple devices) with an active subscription: it stores encrypted data on behalf of the app and cannot be used on its own.
- The node holds ciphertext only. It never has your encryption or signing keys.
- Each release publishes the program files together with a signed `release.json` (version, download addresses, SHA-256 per architecture). The ToE app checks the signature and the checksum before anything is installed or run. If you download a file by hand, compare its SHA-256 with `release.json` first.
- Supported: Linux x86_64 (static binary). More architectures will appear here when they are released.

Installation is done from the ToE app, which generates the install script for your server.
