# scoop-bacio

[Scoop](https://scoop.sh) bucket for **[bacio](https://github.com/mrgeoffrich/bacio)** — a local-first issue tracker for AI agents, with CLI and TUI.

## Install

```powershell
scoop bucket add bacio https://github.com/mrgeoffrich/scoop-bacio
scoop install bacio
```

Upgrade later with `scoop update bacio`, uninstall with `scoop uninstall bacio`.

## How this bucket is updated

`bucket/bacio.json` is rendered and pushed automatically by the [release workflow](https://github.com/mrgeoffrich/bacio/blob/main/.github/workflows/release.yml) in the main bacio repo on every tagged release. Don't hand-edit the manifest here — changes will be overwritten on the next release. File issues and PRs against [mrgeoffrich/bacio](https://github.com/mrgeoffrich/bacio) instead.
