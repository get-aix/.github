# Contributing

Thanks for your interest in improving projects maintained under [get-aix](https://github.com/get-aix).

- **Bugs:** Open an issue in the affected repository with the version, platform, expected behavior, actual behavior, and a minimal reproduction.
- **Feature requests:** Describe the problem you want to solve before proposing an implementation.
- **Pull requests:** Keep changes focused, link the relevant issue when possible, and document user-visible behavior changes.
- **Security:** Do not paste API keys, OAuth tokens, environment secrets, or sensitive logs into issues or pull requests. Report security issues privately using the repository's security reporting instructions.

For changes to [aix](https://github.com/get-aix/aix), run these checks where applicable:

```sh
cargo fmt --all -- --check
cargo clippy --all-targets -- -D warnings
cargo test
```

Individual repositories may define additional or different contribution requirements. Check their local contribution guides first.
