<div align="center">

# asdf-tspin [![Build](https://github.com/donaldguy/asdf-tspin/actions/workflows/build.yml/badge.svg)](https://github.com/donaldguy/asdf-tspin/actions/workflows/build.yml) [![Lint](https://github.com/donaldguy/asdf-tspin/actions/workflows/lint.yml/badge.svg)](https://github.com/donaldguy/asdf-tspin/actions/workflows/lint.yml)

[tspin](https://github.com/bensadeh/tailspin) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add tspin
# or
asdf plugin add tspin https://github.com/donaldguy/asdf-tspin.git
```

tspin:

```shell
# Show all installable versions
asdf list-all tspin

# Install specific version
asdf install tspin latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tspin latest

# Now tspin commands are available
tspin --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/donaldguy/asdf-tspin/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Donald Guy](https://github.com/donaldguy/)
