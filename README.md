# Buzz Causeway releases

Builds of the [Buzz](https://github.com/block/buzz) desktop app with Causeway's
patch stack: each release is an upstream Buzz desktop release plus a few
patches that are on their way upstream or that only Causeway needs. This repo
holds releases only; the patch stack lives in a private repo.

## Install

Download the file for your platform from the
[latest release](https://github.com/ddfourtwo/buzz-causeway-releases/releases/latest):

| Platform | File |
|---|---|
| macOS, Apple Silicon | `Buzz_<version>_aarch64.dmg` |
| macOS, Intel | `Buzz_<version>_x64.dmg` |
| Windows | `Buzz_<version>_x64-setup_unsigned.exe` |
| Linux | `.AppImage` (updates itself) or `.deb` (does not) |

- **macOS:** open the DMG and drag Buzz into Applications, replacing the
  official app if you have it. Builds are signed and notarized.
- **Windows:** the installer is not code-signed yet, so SmartScreen warns
  once: choose **More info → Run anyway**.

Your communities, agents and keys carry over from the official app: both use
the same app identity.

## Updates

Installed copies check this repo and update themselves. They no longer follow
the official Buzz release channel. To go back to official Buzz, install it from
[block/buzz releases](https://github.com/block/buzz/releases) over this one.
