# Code documentation

Here is `Asciidoc` code documentation generated using [Zshelldoc](https://github.com/zdharma/zshelldoc).
There are `4` source files, the main one is [zplugin.zsh](zplugin.zsh.adoc). The documentation
lists all functions, interactions between them, and their comments.

Github allows to directly view `Asciidoc` documents:
 * [zplugin.zsh](zplugin.zsh.adoc) – always loaded, in `.zshrc`
 * [zplugin-side.zsh](zplugin-side.zsh.adoc) – common functions, loaded by `*-install` and `*-autoload` scripts
 * [zplugin-install.zsh](zplugin-install.zsh.adoc) – functions used only when installing a plugin or snippet
 * [zplugin-autoload.zsh](zplugin-autoload.zsh.adoc) – functions used only in interactive `Zplugin` invocations

# PDFs, man pages, etc.

Formats other than `Asciidoc` can be produced by using provided Makefile. For example, issuing
`make pdf` will create and populate a new directory `pdf` (requires `asciidoctor`, install with
`gem install asciidoctor-pdf --pre`).