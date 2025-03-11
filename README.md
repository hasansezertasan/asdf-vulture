<div align="center">

# asdf-vulture [![Build](https://github.com/hasansezertasan/asdf-vulture/actions/workflows/build.yml/badge.svg)](https://github.com/hasansezertasan/asdf-vulture/actions/workflows/build.yml) [![Lint](https://github.com/hasansezertasan/asdf-vulture/actions/workflows/lint.yml/badge.svg)](https://github.com/hasansezertasan/asdf-vulture/actions/workflows/lint.yml)

[vulture](https://github.com/jendrikseipp/vulture) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add vulture
# or
asdf plugin add vulture https://github.com/hasansezertasan/asdf-vulture.git
```

vulture:

```shell
# Show all installable versions
asdf list-all vulture

# Install specific version
asdf install vulture latest

# Set a version globally (on your ~/.tool-versions file)
asdf global vulture latest

# Now vulture commands are available
vulture --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/hasansezertasan/asdf-vulture/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Hasan Sezer Taşan](https://github.com/hasansezertasan/)
