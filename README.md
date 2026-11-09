# homebrew-hearsay

Homebrew tap for [hearsay](https://github.com/Larry8668/hearsay) — live, offline me/them
transcripts of your calls, from the menu bar (macOS 14.2+, Apple Silicon).

```sh
brew tap Larry8668/hearsay
brew trust Larry8668/hearsay       # Homebrew 7+: third-party taps must be trusted
brew install --cask hearsay
```

The app is signed with a self-signed certificate and not notarised; the cask removes the
quarantine attribute after install so it opens normally. On first launch it downloads the speech
model and asks for Microphone access; System Audio Recording is requested the first time you
start listening.
