# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test pint git@github.com:wbollock/asdf-pint.git "pint version"

# or for true local development
asdf plugin test pint . "pint version"
```

Tests are automatically run in GitHub Actions on push and PR.
