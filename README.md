# SandHouse releases

Downloads of the SandHouse desktop app. For which file to pick and how to
install it, see **[sandhouse.app/download](https://sandhouse.app/download)**.

| File | For |
|---|---|
| `SandHouse-windows-x64-setup.exe` | Windows 10 and 11: the installer |
| `SandHouse-windows-x64.msi` | Windows, for managed installs (Intune, Group Policy) |
| `sandhouse-linux-amd64.deb` | Debian, Ubuntu, Mint, Pop!_OS |
| `sandhouse-linux-x86_64.rpm` | Fedora, openSUSE, RHEL |
| `SandHouse-linux-x86_64.AppImage` | Any other Linux distribution |
| `SHA256SUMS` | Checksums of all of the above |

On NixOS or with Nix, use the flake instead:
[Retomodo/sandhouse-nix-flake](https://github.com/Retomodo/sandhouse-nix-flake).

macOS is coming soon.

## Checking a download

In the folder you downloaded to, with `SHA256SUMS` beside the file:

```sh
sha256sum --check --ignore-missing SHA256SUMS
```

## About this repository

It only holds releases; there's no source code here. Releases are built and
published by SandHouse's own CI, and every file in a release keeps the same
name from version to version, so links to
`releases/latest/download/<file>` always fetch the newest one.

Problems with the app: use the contact link at the bottom of
[sandhouse.app](https://sandhouse.app).
