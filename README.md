# fresh-profile

Use different profiles with fresh.

## Installation

### Install fresh

Run the following line or follow the [manual install instructions].

```bash
bash -c "`curl -sL get.freshshell.com`"
```

### Install fresh-profile

Paste the following line into your shell or add it to your `~/.freshrc` file.

```bash
fresh akatov/fresh-profile bin/fresh-profile --bin
```

## Usage

```bash
# usage instructions
fresh profile --help
# set work profile to personal and emacs profile to live
fresh profile work:personal emacs:live
# unset work and emacs profiles
fresh profile work: emacs:
```
