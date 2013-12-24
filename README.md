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
# set $PROFILE to "personal emacs-live"
fresh profile personal emacs-live
# add work to $PROFILE
fresh profile +work
# remove personal from $PROFILE
fresh profile -personal
```
