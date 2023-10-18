# lab-assistant-rs

A framework for building automations within [Star Atlas](https://staratlas.com/) - SAGE Labs.

See [https://play.staratlas.com]() for more details.

## Rust Setup

See [rustup.rs](https://rustup.rs/) for toolchain installation.

## Development Setup

```
    git submodule init
    git submodule update
    # git submodule update --remote --merge
```

## Usage

Create your own scripts and place them in `lab-notebook/examples`, use `00_skratchpad.rs`
as a template for basic setup and usage.

```
    cargo run -p lab-notebook --example 00_skratchpad
```

## Credits

* Inspired by [Lab-Assistant](https://github.com/ImGroovin/Lab-Assistant).
