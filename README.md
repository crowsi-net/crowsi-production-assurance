# crowsi-production-assurance

Check whether deployment evidence meets the declared prerequisites for production control.

## What you can do

- Review key, release and recovery evidence.
- Report missing assurance requirements before activation.

## Current scope

This library evaluates supplied evidence. Its presence or passing unit tests do not certify a production deployment.

Package distribution is not activated by this documentation. Use the checked-in source and the declared dependency versions; published availability must be verified separately.

## Getting started

Install Rust 1.97 or newer and make the declared dependencies available. Use the configured private registry when a dependency is not distributed publicly. Run from this repository:

```sh
cargo test --locked
```

## Documentation and source

[Usage guide](docs/getting-started.md)

[Schemas](schemas) · [Detailed documentation](docs) · [Implementation and public interfaces](src) · [Verification cases](tests) · [Contributing](CONTRIBUTING.md) · [Security reporting](SECURITY.md) · [License](LICENSE) · [Attribution notices](NOTICE)
