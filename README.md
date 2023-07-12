<div align="center">

# asdf-mold [![Build](https://github.com/dkrautha/asdf-mold/actions/workflows/build.yml/badge.svg)](https://github.com/dkrautha/asdf-mold/actions/workflows/build.yml) [![Lint](https://github.com/dkrautha/asdf-mold/actions/workflows/lint.yml/badge.svg)](https://github.com/dkrautha/asdf-mold/actions/workflows/lint.yml)

[mold](https://github.com/rui314/mold) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add mold
# or
asdf plugin add mold https://github.com/dkrautha/asdf-mold.git
```

mold:

```shell
# Show all installable versions
asdf list-all mold

# Install specific version
asdf install mold latest

# Set a version globally (on your ~/.tool-versions file)
asdf global mold latest

# Now mold commands are available
mold --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/dkrautha/asdf-mold/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [David Krauthamer](https://github.com/dkrautha/)
