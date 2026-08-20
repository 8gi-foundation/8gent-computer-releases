# 8gent Computer Releases

**What this is:** the public download channel for 8gent Computer, a desktop app for macOS.
**Who it is for:** anyone who wants to install or update 8gent Computer.
**How to get it:** download the `.dmg` from [the latest release](https://github.com/8gi-foundation/8gent-computer-releases/releases/latest), open it, and drag **8gent Computer** into `/Applications`.

This repository holds release artifacts only. There is no source code here.

## Requirements

- macOS on Apple Silicon (arm64). Intel Macs are not supported.

## What is in a release

Each release publishes three assets:

| Asset | Purpose |
|-------|---------|
| `8gent-computer-<version>.dmg` | The installer |
| `8gent-computer-<version>.dmg.blockmap` | Delta data used by the in-app updater |
| `latest-mac.yml` | Update manifest read by the in-app updater |

From v0.18.9 onward, an installed copy updates itself on next quit. You only need to
download a `.dmg` by hand for a first install.

## Source

The application source lives in a private repository, `8gi-foundation/8gent-computer`.
Issues and pull requests are not accepted here.

## License

Proprietary. All rights reserved, 8GI Foundation. The releases in this repository are
distributed for use of the application and do not carry an open source licence.
8gent Code, at [8gent.dev](https://8gent.dev), is the Foundation's open source project.
