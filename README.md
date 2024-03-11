<div align="center">

# asdf-swifthooks [![Build](https://github.com/lordcodes/asdf-swifthooks/actions/workflows/build.yml/badge.svg)](https://github.com/lordcodes/asdf-swifthooks/actions/workflows/build.yml) [![Lint](https://github.com/lordcodes/asdf-swifthooks/actions/workflows/lint.yml/badge.svg)](https://github.com/lordcodes/asdf-swifthooks/actions/workflows/lint.yml)

[swifthooks](https://github.com/lordcodes/swifthooks) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `unzip`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add swifthooks
# or
asdf plugin add swifthooks https://github.com/lordcodes/asdf-swifthooks.git
```

swifthooks:

```shell
# Show all installable versions
asdf list-all swifthooks

# Install specific version
asdf install swifthooks latest

# Set a version globally (on your ~/.tool-versions file)
asdf global swifthooks latest

# Now swifthooks commands are available
swifthooks generate
swifthooks version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/lordcodes/asdf-swifthooks/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Andrew Lord](https://github.com/lordcodes/)
