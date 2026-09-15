# homebrew-fliiifenleger

Personal [Homebrew](https://brew.sh) tap for
[`fliiifenleger`](https://github.com/cmahnke/fliiifenleger) — a Java-based
command-line tool for generating and validating static IIIF images.

Formulae in this tap are published automatically by the `release.yml`
workflow of the main repo (via
[`homebrew-releaser`](https://github.com/marketplace/actions/homebrew-releaser))
on every `v*` tag — do not edit `Formula/*.rb` by hand, changes will be
overwritten on the next release.

## Install

```sh
brew tap cmahnke/fliiifenleger
brew install fliiifenleger
fliiifenleger --version
```

Requires Java 21+ (the formula depends on `openjdk@21`) and `jpeg-xl`
for the `jxl` image source — both are installed automatically as formula
dependencies.

## Formulae

<!-- project_table_start -->
| Project | Description | Install |
| ------- | ----------- | ------- |
| [fliiifenleger](https://github.com/cmahnke/fliiifenleger) | Java-based static IIIF tiler | `brew install fliiifenleger` |
<!-- project_table_end -->

## License

Released under the [MIT License](./LICENSE).
