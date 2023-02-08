# Cameron's Rust Crate Audits

Cameron uses [cargo-vet](https://mozilla.github.io/cargo-vet/) to ensure
third-party Rust dependencies have been audited by Cameron or another trusted
entity.

This repository automatically
[aggregates](https://mozilla.github.io/cargo-vet/multiple-repositories.html)
Cameron's audits from various repositories to make them easily reusable by
others.

To import Cameron's audits into another cargo-vet instance, add the following
lines to your `config.toml`:

```
[imports.cameron]
url = "https://raw.githubusercontent.com/cameroncros/supply-chain/main/audits.toml"
```
