<div align="center">

# asdf-kcl [![Build](https://github.com/starkers/asdf-kcl/actions/workflows/build.yml/badge.svg)](https://github.com/starkers/asdf-kcl/actions/workflows/build.yml) [![Lint](https://github.com/starkers/asdf-kcl/actions/workflows/lint.yml/badge.svg)](https://github.com/starkers/asdf-kcl/actions/workflows/lint.yml)

[kcl](https://kcl-lang.io) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-kcl  ](#asdf-kcl--)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.


You also need compatible hardware/OS:
- Linux
  - amd64
- OSX/Darwin
  - amd64
  - arm64

# Install

Plugin:

```shell
asdf plugin add kcl
# or
asdf plugin add kcl https://github.com/starkers/asdf-kcl.git
```

kcl:

```shell
# Show all installable versions
asdf list-all kcl

# Install specific version
asdf install kcl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kcl latest

# Now kcl commands are available
kcl --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

Credits for the amazing kcl-lang to:

[KCL contributors](https://github.com/kcl-lang/kcl/graphs/contributors)

# License

See [LICENSE](LICENSE) © [David Stark](https://github.com/starkers/)
