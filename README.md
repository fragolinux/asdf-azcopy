<div align="center">

# asdf-azcopy [![Build](https://github.com/fragolinux/asdf-azcopy/actions/workflows/build.yml/badge.svg)](https://github.com/fragolinux/asdf-azcopy/actions/workflows/build.yml) [![Lint](https://github.com/fragolinux/asdf-azcopy/actions/workflows/lint.yml/badge.svg)](https://github.com/fragolinux/asdf-azcopy/actions/workflows/lint.yml)


[azcopy](https://github.com/Azure/azure-storage-azcopy) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add azcopy
# or
asdf plugin add azcopy https://github.com/fragolinux/asdf-azcopy.git
```

azcopy:

```shell
# Show all installable versions
asdf list-all azcopy

# Install specific version
asdf install azcopy latest

# Set a version globally (on your ~/.tool-versions file)
asdf global azcopy latest

# Now azcopy commands are available
azcopy --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/fragolinux/asdf-azcopy/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Antonio Fragola](https://github.com/fragolinux/)
