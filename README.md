# serde_aws_query_ce [![Build](https://github.com/local-cloud-rs/serde_aws_query_ce/actions/workflows/ci.yaml/badge.svg)](https://github.com/local-cloud-rs/serde_aws_query_ce/actions/workflows/ci.yaml) [![Latest Version]][crates.io] [![Documentation]][docs-rs] 

[Latest Version]: https://img.shields.io/crates/v/serde_aws_query_ce.svg
[crates.io]: https://crates.io/crates/serde_aws_query_ce
[Documentation]: https://docs.rs/serde_aws_query_ce/badge.svg
[docs-rs]: https://docs.rs/serde_aws_query_ce/

This is a Rust library for serializing to and deserializing from
[AWS Query string](https://smithy.io/2.0/aws/protocols/aws-query-protocol.html?highlight=query#aws-protocols-awsqueryname-query-key-naming).

Installation
============

```toml
[dependencies]
serde_aws_query_ce = "0.1"
```

Feature Coverage
================

1. Serialization

- [ ] Simple struct support
- [ ] Vec support
- [ ] Enum support
- [ ] [xmlFlattened](https://smithy.io/2.0/spec/protocol-traits.html#xmlflattened-trait) support

_**Note**: serialization to AWS Query string will be added later._

2. Deserialization

- [x] Simple struct support
- [x] Vec support
- [x] Enum support
- [x] Flattened Vec support
- [ ] AWS Smithy types

License
=======
The library is licenced under Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
