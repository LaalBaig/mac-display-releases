# SecondMac

Turn a spare Mac into a second display for the Mac you actually work on —
over your local network, or a direct cable.

This repository hosts **downloads and release notes only**. It contains no
source code: SecondMac is a commercial app, not open source. (GitHub attaches
"Source code" links to every release automatically; those archives contain
only this README.)

Grab the latest build from the
[Releases page](https://github.com/LaalBaig/mac-display-releases/releases).

## What's in a release

Each release has two apps, and they go on **different Macs**:

| App | Runs on | What it does |
| --- | --- | --- |
| **SecondMac Sender** | The Mac whose screen you want to extend | Creates a virtual display and streams it |
| **SecondMac Receiver** | The spare Mac acting as the monitor | Shows the incoming stream full-screen |

Install the **Sender** on the computer you're working from, and the
**Receiver** on the Mac you want to use as the extra screen.

## Requirements

- macOS 12.3 or later on both Macs
- Both Macs on the same network, or connected directly by Ethernet /
  Thunderbolt / USB-C
- The Sender needs **Screen Recording** permission (macOS prompts on first
  launch)

Both apps are universal binaries, signed and notarized by Apple, and run
natively on Apple Silicon and Intel Macs.

## Licensing

The Sender is free to use for 30 days. After that it needs a license key —
one purchase covers every Mac you own, and it activates offline.

- **Buy a license:** https://baigster65.gumroad.com/l/secondmac
- **Lost your key?** https://secondmac-licensing.laalbaig.workers.dev/recover
  (enter the email you bought with)

The Receiver is never licensed — install it on as many Macs as you like.

## Reporting a problem

Please open an [issue](https://github.com/LaalBaig/mac-display-releases/issues)
with your macOS version, both Mac models, and how the two are connected
(Wi-Fi, Ethernet, direct cable).
