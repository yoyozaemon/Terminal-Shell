# Terminal-Shell
  Terminal Shell using Rust

![](https://github.com/yoyozaemon/Terminl-Shell/blob/master/demo.gif?raw=true)


## Installation

To build the project you will need the Nightly [Rust compiler](https://rustup.rs/). You'll need to activate the nightly mode

```
rustup default nightly
rustup update
```

Clone the repo

```
git clone https://github.com/yoyozaemon/Terminal-Shell
```

Enter the directory and run the project

```
cd Terminal-Shell
cargo run
```

## Running tests

### Unit tests

The tests rely on environment variables so they cannot be ran in parallel. You can run unit tests with

```
cargo test -- --test-threads=1
```

