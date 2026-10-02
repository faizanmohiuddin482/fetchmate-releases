# FetchMate — Releases

Download builds of **FetchMate**, the API client that reads your endpoints and
writes the requests for you.

→ **[fetchmate.vercel.app](https://fetchmate.vercel.app)** · **[Latest release](../../releases/latest)**

This repository contains **no source code** — it exists only to host release
binaries and release notes.

## Install

### macOS (Apple Silicon)

1. Download the `.dmg` from [the latest release](../../releases/latest).
2. Open it and **drag FetchMate to your Applications folder**. Don't run it from
   the mounted disk image — it stays quarantined there and won't launch.
3. These builds aren't notarized yet, so the first launch is blocked with
   *"Apple could not verify FetchMate is free of malware."* To get past it:

   **System Settings → Privacy & Security →** scroll to **Security** →
   *"FetchMate was blocked…"* → **Open Anyway** → authenticate.

   Note that `Open Anyway` only appears for about an hour after a blocked
   launch attempt. If you don't see it, try opening the app again first.

   Or, from a terminal:

   ```sh
   xattr -dr com.apple.quarantine /Applications/FetchMate.app
   ```

macOS remembers the choice, so later launches are normal.

> **Not** right-click → Open. Apple removed that bypass in macOS 15, so on any
> current Mac it does nothing.

Signed and notarized builds are coming; until then this step is expected, not a
sign that anything is wrong.

## Reporting issues

Open an issue here, or email <faizanmohiuddin.dev@gmail.com>.
