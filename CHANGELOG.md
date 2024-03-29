# Changelog

All notable changes to the "pest" extension will be documented in this file.

## 0.0.1 (2018-04-02)

-   Add simple highlighting of strings, comments and names.

## 0.0.2 (2018-11-17)

-   Add highlighting for builtin variables (`COMMENT`, `WHITESPACE`), operations
    (`PUSH`, `POP`, `PEEK`) and constants.
-   Add highlighting of multiline comments (nestable).

## 0.1.0 (2021-07-19)

-   Identifiers with capital letters are now recognized as an identifier.
-   `@`, `$`, `_`, `*` and `?` are now highlighted as as operators.

## 0.2.0 (2021-09-13)

-   Fix nested comments.
-   Highlight `{m, n}` repetitions.

## 0.3.0 (2022-08-29)

-   Add the `fileTypes` field so that the filename is correctly matched for
    editors other than vscode.

## 0.4.0 (2023-01-17)

-   Add support for bracket coloring.
-   Add support for autoclosing multi-line comments.
-   Add support for folding.
-   Change the autoclosing brackets to not autoclose inside of strings.

## 0.4.1 (2023-04-09)

-   Rename the extension to 'Pest Syntax Highlighter'.
