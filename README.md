# poison

> Utilities for writing poisoned types.

## [Documentation](https://crates.fyi/crates/poison/0.1.0)

Provides the `Poison` and `RawPoison` types for use when implementing
structures such as shareable locks that should use poisoning to
warn other threads about panicking while holding a guard, which can
leave data in an invalid state.

## Usage

Use the crates.io repository; add this to your `Cargo.toml` along
with the rest of your dependencies:

```toml
[dependencies]
poison = "0.1"
```

## Author

[Jonathan Reem](https://medium.com/@jreem) is the primary author and maintainer of poison.

## License

MIT

