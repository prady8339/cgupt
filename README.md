# cgupt

Simple website blocker CLI tool for macOS and Linux.

![terminal](https://github.com/user-attachments/assets/5290e15e-a71a-4982-9114-8523dded4d31)


## Installation

```bash
brew install cgupt
```

## Usage

Block domains:

```bash
cgupt block <name1> [name2 ...]      # Block domains (all common TLDs)
cgupt b <name1> [name2 ...]          # Shortcut for block
```

Unblock domains:

```bash
cgupt unblock <name1> [name2 ...]    # Unblock all TLDs
cgupt ub <name1> [name2 ...]         # Shortcut for unblock
```

List blocked domains:

```bash
cgupt list                           # List blocked base names
cgupt ls                             # Shortcut for list
```

Help:

```bash
cgupt help                            # Show help
cgupt h                               # Shortcut for help
```

## License

MIT
