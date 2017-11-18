### Scaffolding a new executable projects

* `cargo new <name> --bin`

Sources live inside `src` and the `Cargo.toml` file contains info about the project.

### Building the project

* `cargo build`

This command will output a `target` directory and file named `Cargo.lock`. To
build a binary for release, append the `--release` argument.

### Running the project

* `cargo run` for development
* `cargo run --release` for release
