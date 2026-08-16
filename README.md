# MacDisplay

Use a spare Mac as a second display for another Mac, over your local network or
a direct cable.

This repository hosts **downloads and release notes only** — it contains no
source code. Grab the latest build from the
[Releases page](https://github.com/LaalBaig/mac-display-releases/releases).

## What's in a release

Each release contains two apps:

| App | Runs on | What it does |
| --- | --- | --- |
| **MacDisplay Sender** | The Mac whose screen you want to extend | Creates a virtual display and streams it |
| **MacDisplay Receiver** | The spare Mac acting as the monitor | Shows the incoming stream full-screen |

Install the **Sender** on the computer you're working from, and the
**Receiver** on the Mac you want to use as the extra screen.

## Requirements

- macOS 12.3 or later on both Macs
- Both Macs on the same network, or connected directly by Ethernet /
  Thunderbolt / USB-C
- The Sender needs **Screen Recording** permission (macOS prompts on first
  launch)

The Receiver ships as a universal binary and runs natively on both Apple
Silicon and Intel Macs.

## Reporting a problem

Please open an [issue](https://github.com/LaalBaig/mac-display-releases/issues)
with your macOS version, both Mac models, and how the two are connected
(Wi-Fi, Ethernet, direct cable).
