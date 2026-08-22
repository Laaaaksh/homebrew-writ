# homebrew-writ

Homebrew tap for [writ](https://github.com/Laaaaksh/writ).

```
brew tap laaaaksh/writ
brew trust laaaaksh/writ
brew install Laaaaksh/writ/writ
```

The `brew trust` step is required once: current Homebrew refuses to load formulae from
third-party taps it has not been told to trust.

The formula in `Formula/` is published automatically by goreleaser on each release.
