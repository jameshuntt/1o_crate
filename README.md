# o1

The 1o main suite (crates.io: [`o1`](https://crates.io/crates/o1)).

This repository was created from the published 0.1.0 source of `o1`, downloaded from crates.io and laid out
as `cargo package` packs it (Cargo.toml as written, Cargo.lock, src/lib.rs). Before this, the crate's
`repository` link pointed here and found nothing.

## Releasing

Bump `version` in Cargo.toml, add a dated `## <version> (YYYY-MM-DD)` entry to CHANGELOG.md, and push to
`main`. CI (.github/workflows/ci.yml) runs the tests and clippy, then publishes that version to crates.io.

## License

MIT OR Apache-2.0.
