[![travis-ci](https://travis-ci.com/karlbateman/lance.svg?token=TZoXB7xVmiZs8swxHAEg&branch=develop)](https://travis-ci.com/github/karlbateman/lance/builds)

# Lance

> Mandlebrot set visualisation CLI

## Introduction

This is a [Rust](https://www.rust-lang.org/) program which plots the [Mandelbrot set](https://en.wikipedia.org/wiki/Mandelbrot_set) and creates a `.png` output file.
Lance is a work-in-progress and as such it's lacking features which will be added over time.

## Compile

Once this program is compiled using the command below, copy the binary file located at `./target/release/lance` and place it on your `$PATH`.

```
cargo build --release
```

## Launch

Alternatively you can run this program without compiling it first using the command below.

```
cargo run --release mandelbrot.png 4000x3000 -1.20,0.35 -1,0.20
```

## Tests

Unit tests can be launched by running the command below.

```
cargo test
```

## License

[BSD](LICENSE) © [@karlbateman](https://github.com/karlbateman)
