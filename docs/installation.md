---
description: Installation instructions for zizmor.
---

# Installation

## From package managers

`zizmor` is available within several packaging ecosystems.

=== "crates.io"

    You can install `zizmor` from <https://crates.io> with `cargo`:

    ```bash
    cargo install zizmor
    ```

=== "Homebrew"

    `zizmor` is provided by [Homebrew](https://brew.sh/):

    ```bash
    brew install zizmor
    ```

=== "Nix"

    !!! note

        This is a community-maintained package.

    ```bash
    # without flakes
    nix-env -iA nixos.zizmor

    # with flakes
    nix profile install nixpkgs#zizmor
    ```

=== "Other ecosystems"

    !!! info

        Are you interested in packaging `zizmor` for another ecosystem?
        Let us know by [filing an issue](https://github.com/woodruffw/zizmor/issues/new)!

    The badge below tracks `zizmor`'s overall packaging status.

    [![Packaging status](https://repology.org/badge/vertical-allrepos/zizmor.svg)](https://repology.org/project/zizmor/versions)



## From source

!!! warning

    Most ordinary users **should not** install directly from `zizmor`'s
    source repository. No stability or correctness guarantees are made about
    direct source installations.

You can install the latest unstable `zizmor` directly from GitHub with `cargo`:

```bash
cargo install --git https://github.com/woodruffw/zizmor
```
