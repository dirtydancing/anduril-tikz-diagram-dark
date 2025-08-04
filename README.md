# Diagram for the Andúril 2 UI, dark mode edition

![Diagram for the Andúril 2 UI, dark mode edition](https://github.com/dirtydancing/anduril-tikz-diagram-dark/releases/latest/download/anduril-tikz-diagram-dark.png "Andúril 2 UI, dark mode edition")

## Download

Check the
[Release](https://github.com/dirtydancing/anduril-tikz-diagram-dark/releases)
(for Andúril 2 release 2025-07-07 only).

For recent changes, check the [Changelog](CHANGELOG.md).

## Further Information

This is an exemplary dark mode edition of the
[generic diagram](https://github.com/dirtydancing/anduril-tikz-diagram).
I am focusing on the standard, generic diagram; further details are
available over there.

The corresponding two commands are:

`lualatex anduril-tikz-diagram-dark.tex`

`pdfcrop --bbox '16 16 825 579' --margins 3 anduril-tikz-diagram-dark.pdf && pdftoppm -png -r 300 -singlefile anduril-tikz-diagram-dark-crop.pdf anduril-tikz-diagram-dark`
