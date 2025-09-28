# 7b common scripts for Rust

## Purpose
The scripts used for building Rust projects.

Using the scripts tremendously reduces efforts of building
any project, making it simpler and faster than using Cargo.

## How to use
Examples of a use are provided inside scripts.
For example,
```
project  =modu
main=test
common =../simscript/comm-build.7b:file
crate_dir=../crates
comp opts=[]

include(common);
```
The typical script name is `bee.7b`. **7b** automatically looks for such file, so
just type **rb**, and the script will be executed.

## Rust compiler access
Unless you use `rustup`, you need to add the path to the compiler in `~/.profile` like
> . "$HOME/projects/simscript/setrustenv"

Modify paths accordingly your environment.

## Other languages

There are also scipts to build Java projects.