# Static binaries for clang-tools

Binaries available for:

 - Linux
 - macOS (both Intel and Apple Silicon)
 - Windows

Tools:

- `clang-format`
- `clang-query`
- `clang-tidy`
- `clang-apply-replacements`

## Proto

Plugins available for [proto](https://moonrepo.dev/proto):

### `clang-format`

```sh
proto plugin add clang-format "https://raw.githubusercontent.com/davidwinter/static-clang-tools-binaries/main/proto/clang-format.toml"
proto install clang-format
```

### `clang-query`

```sh
proto plugin add clang-query "https://raw.githubusercontent.com/davidwinter/static-clang-tools-binaries/main/proto/clang-query.toml"
proto install clang-query
```

### `clang-tidy`

```sh
proto plugin add clang-tidy "https://raw.githubusercontent.com/davidwinter/static-clang-tools-binaries/main/proto/clang-tidy.toml"
proto install clang-tidy
```

### `clang-apply-replacements`

```sh
proto plugin add clang-apply-replacements "https://raw.githubusercontent.com/davidwinter/static-clang-tools-binaries/main/proto/clang-apply-replacements.toml"
proto install clang-apply-replacements
```

_A big shout out to https://github.com/muttleyxd/clang-tools-static-binaries for the original workflow code that made this possible._
