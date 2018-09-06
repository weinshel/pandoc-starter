# article

These starter files can be used to generate a simple article, as you're familiar
with from LaTeX's `article` document class.

## Dependencies

There are a number of build dependencies for these starter files:

- [Pandoc], a universal document converter
- [LaTeX], a document preparation system
- `pandoc citeproc`, which connects bibliographies with Pandoc

[Pandoc]: https://pandoc.org/
[LaTeX]: https://www.latex-project.org/

Installation instructions vary depending on your system. See the linked websites
for more information.

On Macs, you can use [Homebrew](https://brew.sh) to install `pandoc` and `pandoc-citeproc`:

```
$ brew install pandoc pandoc-citeproc
```

## Usage

1. Copy these starter files wherever you'd like.
1. Rename `sample.md` to `<filename>.md`
1. Edit the `TARGET` variable at the top of the [Makefile] to equal `<filename>`
1. Write your content in `<filename>.md`
    - Be sure to adjust the information like the `title` and `author` at the top
      of the file
1. Read the [Makefile's documentation][Makefile].

[Makefile]: src/Makefile

## License

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](https://jez.io/MIT-LICENSE.txt)
