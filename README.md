# pre-commit-hooks-misc

Some pre-commit hooks for different language and tools

To use these hooks, simply place the following in your `.pre-commit-config.yaml`:

```yaml
repos:
-   repo: https://github.com/tctony/pre-commit-hooks-misc
    rev: master
    hooks:
    -   id: swiftlint
    -   id: bazel
```

More details below.

## swiftlint

```shell
brew install swiftlint
```

## bazel
```sh
go get github.com/bazelbuild/buildtools/buildifier
```
