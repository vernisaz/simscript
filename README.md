# RB common scripts

## Purpose
The scripts used for building projects in different languages.

Using the scripts tremendously reduces efforts of building
any project in Rust, making it simpler and faster than using Cargo.

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
So a final script will include the common script and required for it variables.
A typical script name is `bee.7b`. **rb** automatically looks for files with such name pattern, so
just type **rb**, and the script will be executed.

## Rust compiler access
Unless you use `rustup`, you need to add the path to the compiler in `~/.profile` like
> . "$HOME/projects/simscript/setrustenv"

Modify paths accordingly your environment.


## Other languages

There are also scripts to build Java, Swift and C projects.