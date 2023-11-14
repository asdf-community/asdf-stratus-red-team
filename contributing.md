# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test stratus-red-team https://github.com/vthiery/asdf-stratus-red-team.git "stratus version"
```

Tests are automatically run in GitHub Actions on push and PR.
