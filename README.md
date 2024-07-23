# Automate - Simple Git Command Line Tool

## Overview

A simple command line tool written in Rust. It automates the process of adding all files, committing changes, and pushing them to the remote repository. This tool is designed to streamline the Git workflow, making it faster and more convenient.

## Usage

To use `automate`, follow these steps:

1. Navigate to the root directory of your Git repository in the terminal.

2. Run the following command:

```bash
automate
```

This command will execute the tool and perform the following operations:

1. Add all files recursively to the Git repository.
2. Commit all changes with a randomly generated commit message.
3. Push the changes to the remote repository (origin main branch).

## Installation
1. Clone the repository:

```bash
git clone <url>
```

2. Navigate to the project directory:

```bash
cd automate
```

3. Build the project using Cargo:

```bash
cargo build --release
```

4. Install the binary:

```bash
cargo install --path .
```

## Dependencies

- `names`: This dependency is used to generate random commit messages. You can find more information about this crate [here](https://crates.io/crates/names).

- `std::os`: This module is part of the Rust standard library and is used for interacting with the operating system. It is used in this project for handling process exit codes.

## License

This project is released under the MIT License - see the [LICENSE](LICENSE) file for details.
