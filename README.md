# pest syntax highlighter

A syntax highlighter for [pest](https://github.com/pest-parser/pest)'s PEG
grammar files.

**Enjoy!**

## Contributors

-   Thanks [flying-sheep](https://github.com/flying-sheep) for contributing for
    version 0.0.2!
-   Thanks to [drmason13](https://github.com/drmason13) for contributing for
    version 0.1.0 and 0.2.0!

## Release Notes

### 0.0.1

Initial release.

### 0.0.2

-   Add highlighting for Builtin Variables (`COMMENT`, `WHITESPACE`), Operations
    (`PUSH`, `POP`, `PEEK`) and Constants.
-   Add highlighting of Multiline comments (nestable).

### 0.1.0

-   Identifiers with capital letters are now recognized as an identifier.
-   `@`, `$`, `_`, `*` and `?` are now highlighted as as operators.

### 0.2.0

-   Fix nested comments.
-   Hightlight `{m, n}` repetitions.
