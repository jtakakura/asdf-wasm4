<div align="center">

# asdf-wasm4 [![Build](https://github.com/jtakakura/asdf-wasm4/actions/workflows/build.yml/badge.svg)](https://github.com/jtakakura/asdf-wasm4/actions/workflows/build.yml) [![Lint](https://github.com/jtakakura/asdf-wasm4/actions/workflows/lint.yml/badge.svg)](https://github.com/jtakakura/asdf-wasm4/actions/workflows/lint.yml)


[wasm4](https://github.com/aduros/wasm4) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add wasm4
# or
asdf plugin add wasm4 https://github.com/jtakakura/asdf-wasm4.git
```

wasm4:

```shell
# Show all installable versions
asdf list-all wasm4

# Install specific version
asdf install wasm4 latest

# Set a version globally (on your ~/.tool-versions file)
asdf global wasm4 latest

# Now wasm4 commands are available
w4 --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jtakakura/asdf-wasm4/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Junji Takakura](https://github.com/jtakakura/)
