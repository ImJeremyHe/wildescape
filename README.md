# wildescape

[![build status](https://github.com/ImJeremyHe/wildescape/workflows/Build/badge.svg)](https://github.com/ImJeremyHe/wildescape/actions?workflow=Build)
[![docs](https://docs.rs/wildescape/badge.svg)](https://docs.rs/wildescape)
[![downloads](https://img.shields.io/crates/v/wildescape.svg?color=orange)](https://crates.io/crates/wildescape)
[![crate](https://badgen.net/crates/d/wildescape)](https://crates.io/crates/wildescape)
[![license](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![codecov](https://img.shields.io/codecov/c/github/ImJeremyHe/wildescape/master)](https://codecov.io/gh/ImJeremyHe/wildescape)

**This is a fork of [wildmatch](https://github.com/becheran/wildmatch)**, but with an escape character defined.

Match strings against a simple wildcard pattern. Tests a wildcard pattern `p` against an input string `s`. Returns true only when `p` matches the entirety of `s`.

See also the example described on [wikipedia](https://en.wikipedia.org/wiki/Matching_wildcards) for matching wildcards.

- `?` matches exactly one occurrence of any character.
- `*` matches arbitrary many (including zero) occurrences of any character.
- `~` is the escaped character for matching `?`, `*` and `~`.
