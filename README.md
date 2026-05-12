# scoop-holdon

Scoop bucket for [holdon](https://github.com/imjustprism/holdon) — wait for anything, know why if it doesn't.

## Install

```powershell
scoop bucket add holdon https://github.com/imjustprism/scoop-holdon
scoop install holdon
```

## Update

```powershell
scoop update holdon
```

## Uninstall

```powershell
scoop uninstall holdon
scoop bucket rm holdon
```

## How it works

The manifest in `bucket/holdon.json` downloads the prebuilt Windows binary from the matching GitHub Release on the upstream repo. Scoop's autoupdate hash field tracks the upstream `SHA256SUMS` file so users always get a verified download.

Source code: https://github.com/imjustprism/holdon
