# zig-toml
A TOML parser written in Zig targeting [TOML v0.5.0](https://github.com/toml-lang/toml). The end goal is for the program to be robust, with no crashing given any situation. Though, in its current state this program is probably far from that goal.

There is currently a lack of documentation but the tests contained should give enough of an idea on how to use this.

[Quickstart Guide](https://github.com/darithorn/zig-toml/wiki/Quickstart-Guide)

## Features
- [x] Tables
- [x] Keys (all kinds)
- [x] Single-line strings
- [x] Integers
- [x] Booleans
- [x] Arrays
- [x] Comments
- [ ] Floats
- [ ] Hexadecimal, octal, and binary numbers
- [ ] Multi-line strings
- [ ] String escapes
- [ ] Inline tables
- [ ] Array of tables
- [ ] Time and date

## Building and Usage

This library is self-contained and requires no dependencies.

To build simply run `zig build` and that will output a file called `libtoml.a` that you can link with your program.

If you want to run the tests then use the `zig build test` command.
