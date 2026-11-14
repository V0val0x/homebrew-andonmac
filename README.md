# Homebrew Tap for AndOnMac

Official Homebrew Tap for [**AndOnMac**](https://github.com/V0val0x/AndOnMac) — native macOS app for mirroring and controlling Android smartphones.

## Installation

```bash
brew install --cask V0val0x/andonmac/andonmac
```

Or tap first:

```bash
brew tap V0val0x/andonmac
brew install --cask andonmac
```

## Updating

```bash
brew upgrade --cask andonmac
```

> **Note:** AndOnMac is free and open-source and is distributed without a \$99/year Apple Developer ID notarization. The cask's `postflight` hook automatically clears `com.apple.quarantine` (`xattr -cr`) during installation so you can open the app immediately.
