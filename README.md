# This is NOT the official project but my personal solution!!

# Original sources:

## MacOS/Linux

Just run:

```bash
curl -L https://git.io/rustlings | bash
# Or if you want it to be installed to a different path:
curl -L https://git.io/rustlings | bash -s mypath/
```

This will install Rustlings and give you access to the `rustlings` command. Run it to get started!

## Manually

Basically: Clone the repository, checkout to the latest tag, run `cargo install`.

```bash
git clone https://github.com/rust-lang/rustlings
cd rustlings
git checkout tags/1.0.0 # or whatever the latest version is (find out at https://github.com/rust-lang/rustlings/releases/latest)
cargo install --force --path .
```

`rustlings` was originally written by [Carol](https://github.com/carols10cents)!

