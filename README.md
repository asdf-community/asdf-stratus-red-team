<div align="center">

# asdf-stratus-red-team [![Build](https://github.com/vthiery/asdf-stratus-red-team/actions/workflows/build.yml/badge.svg)](https://github.com/vthiery/asdf-stratus-red-team/actions/workflows/build.yml) [![Lint](https://github.com/vthiery/asdf-stratus-red-team/actions/workflows/lint.yml/badge.svg)](https://github.com/vthiery/asdf-stratus-red-team/actions/workflows/lint.yml)

[stratus-red-team](https://stratus-red-team.cloud/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add stratus-red-team
# or
asdf plugin add stratus-red-team https://github.com/vthiery/asdf-stratus-red-team.git
```

stratus-red-team:

```shell
# Show all installable versions
asdf list-all stratus-red-team

# Install specific version
asdf install stratus-red-team latest

# Set a version globally (on your ~/.tool-versions file)
asdf global stratus-red-team latest

# Now stratus-red-team commands are available
stratus version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/vthiery/asdf-stratus-red-team/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Vincent Thiery](https://github.com/vthiery/)
