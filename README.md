<div align="center">

# asdf-lazydocker [![Build](https://github.com/mfandrade/asdf-lazydocker/actions/workflows/build.yml/badge.svg)](https://github.com/mfandrade/asdf-lazydocker/actions/workflows/build.yml) [![Lint](https://github.com/mfandrade/asdf-lazydocker/actions/workflows/lint.yml/badge.svg)](https://github.com/mfandrade/asdf-lazydocker/actions/workflows/lint.yml)

[lazydocker](https://github.com/mfandrade/lazydocker) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add lazydocker
# or
asdf plugin add lazydocker https://github.com/mfandrade/asdf-lazydocker.git
```

lazydocker:

```shell
# Show all installable versions
asdf list-all lazydocker

# Install specific version
asdf install lazydocker latest

# Set a version globally (on your ~/.tool-versions file)
asdf global lazydocker latest

# Now lazydocker commands are available
lazydocker --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mfandrade/asdf-lazydocker/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Marcelo F Andrade](https://github.com/mfandrade/)
