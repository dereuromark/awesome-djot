# Awesome Djot [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of [Djot](https://djot.net/) resources, tools, editors, and libraries.

[Djot](https://djot.net/) is a light markup syntax created by John MacFarlane (creator of Pandoc and CommonMark). It draws on Markdown's syntax but aims to be more consistent and unambiguous.

## Contents

- [Official Resources](#official-resources)
- [Parsers & Libraries](#parsers--libraries)
- [Editors & IDE Support](#editors--ide-support)
- [Tools](#tools)
- [Converters](#converters)
- [CMS Integration](#cms-integration)
- [Documentation Tools](#documentation-tools)
- [Static Site Generators](#static-site-generators)
- [Learning Resources](#learning-resources)
- [Community](#community)

## Official Resources

- [Djot.net](https://djot.net/) - Official website with playground and documentation.
- [Djot Quick Reference](https://htmlpreview.github.io/?https://github.com/jgm/djot/blob/master/doc/quick.html) - Official quick syntax reference.
- [Djot Syntax Reference](https://htmlpreview.github.io/?https://github.com/jgm/djot/blob/master/doc/syntax.html) - Complete syntax specification.
- [jgm/djot](https://github.com/jgm/djot) - Official reference implementation in JavaScript/TypeScript.
- [jgm/djot.lua](https://github.com/jgm/djot.lua) - Official Lua implementation.

## Parsers & Libraries

### .NET / C#

- [xoofx/markdig](https://github.com/xoofx/markdig) - Markdig has experimental Djot support.

### Elixir

- [paradox460/djot](https://github.com/paradox460/djot) - Elixir wrapper around jotdown.

### Go

- [sivukhin/godjot](https://github.com/sivukhin/godjot) - Djot parser in Go.

### Haskell

- [jgm/djoths](https://github.com/jgm/djoths) - Haskell implementation of Djot.

### JavaScript / TypeScript

- [jgm/djot](https://github.com/jgm/djot) - Official reference implementation. Provides both a library and CLI tool.

### Lua

- [jgm/djot.lua](https://github.com/jgm/djot.lua) - Official Lua implementation, can be used with LuaJIT.

### PHP

- [php-collective/djot-php](https://github.com/php-collective/djot-php) - PHP implementation with extensions and security features.

### Python

- [jgm/djot.py](https://github.com/jgm/djot.py) - Python bindings for the JavaScript implementation.

### Rust

- [hellux/jotdown](https://github.com/hellux/jotdown) - Djot parser and renderer in Rust.

## Editors & IDE Support

### Emacs

- [djot-mode](https://github.com/lrustand/djot-mode) - Major mode for editing Djot files in Emacs.

### JetBrains IDEs

- [Djot Plugin](https://plugins.jetbrains.com/plugin/29244-djot) - Djot support for all JetBrains IDEs.

### Vim / Neovim

- [nvim-treesitter/nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter) - Tree-sitter grammar available for Djot syntax highlighting.

### Visual Studio Code

- [Djot VSCode Extension](https://marketplace.visualstudio.com/items?itemName=pjeby.vscode-djot) - Syntax highlighting and preview for Djot.

## Tools

- [tjot](https://hg.sr.ht/~ser/tjot) - Terminal renderer for Djot with image and table support.

## Converters

- [djot.js CLI](https://github.com/jgm/djot#cli) - Convert Djot to HTML, Pandoc AST, and more.
- [Pandoc](https://pandoc.org/) - Universal document converter with Djot reader/writer support (since version 3.0).

## CMS Integration

- [Djot Markup for WordPress](https://wordpress.org/plugins/djot-markup/) - WordPress plugin with extensions and addons.

## Documentation Tools

- [resilient.sile](https://omikhleia.github.io/resilient.sile/adventures/djot/) - Book production toolchain with Djot support.
- [SEED.html](https://stewarthaines.com/epub/SEED.html) - Browser-based EPUB authoring tool with Djot support.

## Static Site Generators

- [Eleventy](https://www.11ty.dev/) - Can use Djot via plugins.
- [Glaze](https://github.com/josbeir/glaze) - Fast PHP static site generator with native Djot support.
- [gozer](https://git.sr.ht/~dvko/gozer) - Minimalist static site generator with Djot support.
- [Lume](https://lume.land/) - Deno-based SSG with Djot plugin support.

## Learning Resources

### Articles

- 2022: [Beyond Markdown](https://djot.net/misc/draft.html) - John MacFarlane's article explaining the rationale behind Djot.
- 2022: [I've moved my blog to Djot](https://matklad.github.io/2022/12/18/on-djot.html) - Alex Kladov's experience migrating from AsciiDoctor to Djot.
- 2025: [Djot PHP - A Modern Markup Parser](https://www.dereuromark.de/2025/12/09/djot-php-a-modern-markup-parser/) - Introduction to the PHP implementation.
- 2025: [Writing in Djot](https://pdx.su/blog/2025-06-28-writing-in-djot/) - Blog post about using Djot with Elixir and Tableau.

### Tutorials

*Contributions welcome!*

### Cheat Sheets

- [Djot Quick Reference](https://htmlpreview.github.io/?https://github.com/jgm/djot/blob/master/doc/quick.html) - Official quick syntax reference.

## Community

- [GitHub Discussions](https://github.com/jgm/djot/discussions) - Official discussion forum for Djot.
- [GitHub Issues](https://github.com/jgm/djot/issues) - Report bugs and request features.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
