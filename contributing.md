# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test lazydocker https://github.com/mfandrade/asdf-lazydocker.git "lazydocker --help"
```

Tests are automatically run in GitHub Actions on push and PR.
