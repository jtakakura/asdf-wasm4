# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test wasm4 https://github.com/jtakakura/asdf-wasm4.git "w4 --help"
```

Tests are automatically run in GitHub Actions on push and PR.
