# language-latex-plus

LaTeX language with modern tree-sitter grammar and legacy TextMate grammar.

> [!NOTE]
> This package is in maintenance mode. If you use [Lumine](https://github.com/lumine-code/lumine), you may be interested in [language-latex](https://github.com/lumine-code/language-latex), [language-bibtex](https://github.com/lumine-code/language-bibtex), and [language-log](https://github.com/lumine-code/language-log).

## Features

- **Tree-sitter grammar**: LaTeX with syntax highlighting, code folding, indentation, and symbol navigation.
- **TextMate grammar**: fallback for LaTeX, TeX, BibTeX, Beamer, Memoir, and log files.
- **166 snippets**: for common LaTeX constructs (environments, sections, math, etc.).

## Installation

To install `language-latex-plus` search for [language-latex-plus](https://web.pulsar-edit.dev/packages/language-latex-plus) in the Install pane of the Pulsar settings or run `ppm install language-latex-plus`. Alternatively, you can run `ppm install asiloisad-pulsar/language-latex-plus` to install a package directly from the GitHub repository.

## Tree-sitter (modern)

Based on [tree-sitter-latex](https://github.com/latex-lsp/tree-sitter-latex). Used by default when Pulsar's modern tree-sitter parser is enabled.

Provides:
- Accurate syntax highlighting for commands, environments, math, sections, citations, labels, and more
- Code folding for sections, environments, equations, and comments
- Auto-indentation inside environments and brace groups
- Symbol navigation for sections, labels, and command definitions
- Hyperlink and TODO detection in comments

## TextMate (legacy)

Derived from the [TextMate LaTeX bundle](https://github.com/textmate/latex.tmbundle). Used as fallback when tree-sitter is disabled.

Includes grammars for:
- LaTeX (`text.tex.latex`)
- TeX (`text.tex`)
- BibTeX (`text.bibtex`)
- Beamer (`text.tex.latex.beamer`)
- Memoir (`text.tex.latex.memoir`)
- LaTeX log (`text.log.latex`)

## Contributing

Got ideas to make this package better, found a bug, or want to help add new features? Just drop your thoughts on GitHub. Any feedback is welcome!
