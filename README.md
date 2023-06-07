<div align="center">

# asdf-pint [![Build](https://github.com/wbollock/asdf-pint/actions/workflows/build.yml/badge.svg)](https://github.com/wbollock/asdf-pint/actions/workflows/build.yml) [![Lint](https://github.com/wbollock/asdf-pint/actions/workflows/lint.yml/badge.svg)](https://github.com/wbollock/asdf-pint/actions/workflows/lint.yml)

[pint](https://cloudflare.github.io/pint/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-pint  ](#asdf-pint--)
- [Contents](#contents)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Install

Plugin:

```shell
asdf plugin add pint
# or
asdf plugin add pint https://github.com/wbollock/asdf-pint.git
```

pint:

```shell
# Show all installable versions
asdf list-all pint

# Install specific version
asdf install pint latest

# Set a version globally (on your ~/.tool-versions file)
asdf global pint latest

# Now pint commands are available
pint version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/wbollock/asdf-pint/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Will Bollock](https://github.com/wbollock/)
