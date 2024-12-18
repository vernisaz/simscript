# 7b common scripts for Rust

The scripts used by other Rust projects.
Examples of use are provided inside scripts.
For exampe
```
project  =modu
main=test
common =../simscript/comm-build.7b:file
crate_dir=../crates

include(common);
```
Using the scripts tremendously reduces efforts of building
any project, making it simpler and faster than using Cargo.
