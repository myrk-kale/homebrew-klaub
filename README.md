# Homebrew tap for Klaub (moved)

The klaub formula now lives in the shared tap, like the other tools of
[myrk-kale](https://github.com/myrk-kale):

```shell
brew install myrk-kale/tap/klaub
```

If you added this tap earlier, switch with:

```shell
brew uninstall klaub
brew untap myrk-kale/klaub
brew install myrk-kale/tap/klaub
```

This tap is no longer updated after klaub 0.4.0, so `brew upgrade` here will not
bring newer versions.
