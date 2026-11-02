# Panto tap

```sh
brew install --cask AbayAtazhan/panto/panto
```

Or tap first:

```sh
brew tap AbayAtazhan/panto
brew install --cask panto
```

Panto is not notarized yet. If macOS blocks the first launch, use `--no-quarantine` or run:

```sh
xattr -dr com.apple.quarantine /Applications/Panto.app
```

Source: https://github.com/AbayAtazhan/panto
