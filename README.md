# Lore Releases

[Lore](https://uselore.co) gives coding agents a shared engineering memory:
teach one agent once, and the others learn too.

This repository contains its CLI binary releases. Documentation is at
[docs.uselore.co](https://docs.uselore.co).

## Install

macOS or Linux:

```sh
curl -fsSL https://uselore.co/install.sh | bash
```

Windows, in PowerShell:

```powershell
irm https://uselore.co/install.ps1 | iex
```

Then connect your agent: see [Install and connect](https://docs.uselore.co/install).

## What each release contains

- CLI binaries: `lore-darwin-arm64`, `lore-darwin-x64`, `lore-linux-arm64`,
  `lore-linux-x64`, and `lore-windows-x64.exe`.
- The `install.sh` and `install.ps1` installers.
- `SHA256SUMS` and its signature, `SHA256SUMS.sig`. The installers check both
  before installing.
- Setup files for Claude Cowork and GitHub Copilot.
