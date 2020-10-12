<!-- [![Crates.io](https://img.shields.io/crates/v/sbml.svg)](https://crates.io/crates/sbml)
[![Documentation](https://docs.rs/sbml/badge.svg)](https://docs.rs/sbml/) -->
[![Build](https://github.com/carraascomj/rust-sbml/workflows/Build/badge.svg)](https://github.com/carraascomj/rust-sbml)
[![Codecov](https://codecov.io/github/carrascomj/rust-sbml/coverage.svg?branch=master)](https://codecov.io/gh/carrascomj/rust-sbml)

# A parser for SBML
This is a parser for the Systems Biology Markup Language (SBML).

## Example
```rust
let example=r#"<?xml version="1.0" encoding="UTF-8"?>
<sbml xmlns="http://www.sbml.org/sbml/level3/version2/core" level="3" version="2">
    <model timeUnits="second" extentUnits="mole" substanceUnits="mole">
    </model>
</sbml>"#;
let result = parse_document(example);
```
