# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test pint git@github.com:wbollock/asdf-pint.git "pint version"

# the only way I know of testing is literally to push changes and try them with `act` or whatever
```

Tests are automatically run in GitHub Actions on push and PR.
