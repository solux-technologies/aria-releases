# Aria — Download

Aria is a personal AI orchestrator for Windows. This repo hosts the installer
downloads and the auto-update manifest. (Source code lives in the private
[`solux-technologies/aria`](https://github.com/solux-technologies/aria) repo.)

## ⬇️ Download (Windows 10 / 11)

**[Download the latest Aria installer →](https://github.com/solux-technologies/aria-releases/releases/latest/download/Aria_x64-setup.exe)**

That link always points at the newest version. Run it — Aria installs per-user,
**no admin rights needed**.

You can also browse every version on the
[Releases page](https://github.com/solux-technologies/aria-releases/releases/latest).

## 🔄 Updates are automatic

Once installed, Aria checks for updates on launch and every ~30 minutes, and
updates itself in the background. You won't need to come back here — installing
once is enough.

## ⚠️ First-run SmartScreen warning

This build isn't OS-code-signed yet, so Windows SmartScreen shows a blue
*"Windows protected your PC"* box the first time you run the installer. This is
expected (it just means we haven't bought an Authenticode certificate). To
continue:

1. Click **More info**
2. Click **Run anyway**

## What's in the box

A single installer that bundles everything Aria needs (the agent hub, the
notification watcher, and the messaging connectors). No separate downloads, no
configuration — sign in after install and you're running.

---

<sub>The `latest.json` and `.sig` files attached to each release power the
in-app auto-updater — you don't need to download them.</sub>
