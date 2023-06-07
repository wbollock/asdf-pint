# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test pint https://github.com/wbollock/asdf-pint.git "pint version"
```

Tests are automatically run in GitHub Actions on push and PR.
