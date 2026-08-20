# kiroX Bridge Releases

This repository contains signed kiroX Bridge installation and update artifacts.
It intentionally does not contain the kiroX Bridge source code.

## Installation

Download the latest macOS Apple Silicon (`arm64`) DMG from [Releases](../../releases/latest), open it, and drag `kiroX Bridge` into Applications.

Existing installations check this repository for signed updates automatically. The updater verifies every downloaded archive with the public key embedded in the app before installing it.

## Release assets

- `*.dmg`: first-time installation package.
- `*.app.tar.gz`: Tauri automatic-update package.
- `*.app.tar.gz.sig`: signature for the automatic-update package.
- `latest.json`: latest signed-update metadata for the app.
- `*.sha256`: manual integrity checks for downloaded files.
