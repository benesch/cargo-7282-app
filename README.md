# Repro instructions

Reproduction instructions for [cargo#7282]:

```bash
$ git clone https://github.com/benesch/cargo-7282-app.git
$ cd cargo-7282-app
$ cargo build
# Should succeed.
$ cargo build
# Should complain about an unused patch.
```

[cargo#7282]: https://github.com/rust-lang/cargo/issues/7282
