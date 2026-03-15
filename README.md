# Awesome Djot [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of [Djot](https://djot.net/) resources, tools, editors, and libraries.

[Djot](https://djot.net/) is a light markup syntax created by John MacFarlane (creator of Pandoc and CommonMark). It draws on Markdown's syntax but aims to be more consistent and unambiguous.

## Contents

- [Official Resources](#official-resources)
- [Parsers & Libraries](#parsers--libraries)
- [Editors & IDE Support](#editors--ide-support)
- [Tools](#tools)
- [Converters](#converters)
- [Migration](#migration)
- [CMS Integration](#cms-integration)
- [Documentation Tools](#documentation-tools)
- [Static Site Generators](#static-site-generators)
- [Syntax Highlighting](#syntax-highlighting)
- [Sandboxes](#sandboxes)
- [Example Sites](#example-sites)
- [Learning Resources](#learning-resources)
- [Community](#community)

## Official Resources

- [Djot.net](https://djot.net/) - Official website with playground and documentation.
- [Djot Cheatsheet](https://github.com/jgm/djot/blob/master/doc/cheatsheet.md) - Quick syntax reference.
- [Djot Syntax Reference](https://htmlpreview.github.io/?https://github.com/jgm/djot/blob/master/doc/syntax.html) - Complete syntax specification.
- [jgm/djot](https://github.com/jgm/djot) - Official reference implementation in JavaScript/TypeScript.
- [jgm/djot.lua](https://github.com/jgm/djot.lua) - Official Lua implementation.

## Parsers & Libraries

### .NET / C#

- [xoofx/markdig](https://github.com/xoofx/markdig) - Markdig has experimental Djot support.

### Elixir

- [paradox460/djot](https://github.com/paradox460/djot) - Elixir wrapper around jotdown.

### Erlang

- [faelys/djot.erlang](https://github.com/faelys/djot.erlang) - Djot parser in Erlang.

### Gleam

- [lpil/jot](https://github.com/lpil/jot) - Djot parser in Gleam.

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

### Prolog

- [aarroyoc/djota](https://github.com/aarroyoc/djota) - Djot implementation in Prolog.

### Python

- [jgm/djot.py](https://github.com/jgm/djot.py) - Python bindings for the JavaScript implementation.

### Ruby

- [gdiasag/djotter](https://github.com/gdiasag/djotter) - Ruby wrapper for the jotdown Rust crate.

### Rust

- [hellux/jotdown](https://github.com/hellux/jotdown) - Djot parser and renderer in Rust.

### Swift

- [wti/SwiftDjot](https://github.com/wti/SwiftDjot) - Swift wrapper for djot C library interface.

### Zig

- [leroycep/djot.zig](https://github.com/leroycep/djot.zig) - Djot parser implemented in Zig.

## Editors & IDE Support

### Emacs

- [djot-mode](https://github.com/lrustand/djot-mode) - Major mode for editing Djot files in Emacs.

### JetBrains IDEs

- [djot-intellij](https://github.com/php-collective/djot-intellij) - Djot support for all JetBrains IDEs.

### Vim / Neovim

- [nvim-treesitter/nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter) - Tree-sitter grammar available for Djot syntax highlighting.

### Visual Studio Code

- [Djot VSCode Extension](https://marketplace.visualstudio.com/items?itemName=pjeby.vscode-djot) - Syntax highlighting and preview for Djot.

## Tools

- [djoc](https://github.com/kmaasrud/djoc) - Djot document compiler.
- [djotfmt](https://github.com/black-desk/djotfmt) - Djot formatter.
- [tjot](https://hg.sr.ht/~ser/tjot) - Terminal renderer for Djot with image and table support.

## Converters

- [djot.js CLI](https://github.com/jgm/djot#cli) - Convert Djot to HTML, Pandoc AST, and more.
- [djot-php Converters](https://php-collective.github.io/djot-php/guide/converters.html) - PHP converters for HTML, plain text, and custom formats.
- [Pandoc](https://pandoc.org/) - Universal document converter with Djot reader/writer support (since version 3.0).

## Migration

Tools for migrating from other markup formats to Djot.

- [Pandoc](https://pandoc.org/) - Convert Markdown, AsciiDoc, reStructuredText, and more to Djot.

## CMS Integration

- [wp-djot](https://github.com/php-collective/wp-djot) - PHP WordPress plugin with extensions and syntax highlighting.

## Documentation Tools

- [mdbook-djot](https://github.com/dcampbell24/mdbook-djot) - Djot plugin for mdBook.
- [resilient.sile](https://omikhleia.github.io/resilient.sile/adventures/djot/) - Book production toolchain with Djot support.
- [SEED.html](https://stewarthaines.com/epub/SEED.html) - Browser-based EPUB authoring tool with Djot support.

## Static Site Generators

- [djockey](https://github.com/irskep/djockey) - Powerful SSG for technical writing and documentation.
- [Eleventy](https://www.11ty.dev/) - Can use Djot via plugins.
- [Glaze](https://github.com/josbeir/glaze) - Fast PHP static site generator with native Djot support.
- [gozer](https://git.sr.ht/~dvko/gozer) - Minimalist static site generator with Djot support.
- [Lume](https://lume.land/) - Deno-based SSG with Djot plugin support.

## Syntax Highlighting

- [djot.sublime-syntax](https://github.com/sorairolake/djot.sublime-syntax) - Djot syntax highlighting for Sublime Text.
- [djot.tmLanguage.json](https://github.com/php-collective/djot-intellij/blob/main/src/main/resources/textmate/djot.tmLanguage.json) - TextMate grammar for Shiki/VS Code.
- [hljs-djot.js](https://github.com/php-collective/djot-php/blob/master/docs/public/assets/hljs-djot.js) - highlight.js grammar for Djot.
- [tree-sitter-djot](https://github.com/treeman/tree-sitter-djot) - Tree-sitter grammar for Djot.

## Sandboxes

- [Djot Playground](https://djot.net/) - Official online playground.
- [Djot PHP Sandbox](https://sandbox.dereuromark.de/sandbox/djot) - Interactive sandbox for djot-php (most complete version/specs).

## Example Sites

Websites and blogs built with Djot.

- [dereuromark.de](https://www.dereuromark.de/) - PHP/CakePHP developer blog using djot-php.
- [matklad.github.io](https://matklad.github.io/) - Alex Kladov's blog, migrated from AsciiDoctor.
- [pdx.su](https://pdx.su/) - Blog using Djot with Elixir and Tableau.

## Learning Resources

### Articles

- 2022-08: [Beyond Markdown](https://djot.net/misc/draft.html) - John MacFarlane's article explaining the rationale behind Djot.
- 2022-12: [I've moved my blog to Djot](https://matklad.github.io/2022/12/18/on-djot.html) - Alex Kladov's experience migrating from AsciiDoctor to Djot.
- 2025-06: [Writing in Djot](https://pdx.su/blog/2025-06-28-writing-in-djot/) - Blog post about using Djot with Elixir and Tableau.
- 2025-12: [Djot PHP - A Modern Markup Parser](https://www.dereuromark.de/2025/12/09/djot-php-a-modern-markup-parser/) - Introduction to the PHP implementation.

### Tutorials

- [Djot Syntax Guide](https://php-collective.github.io/djot-php/guide/syntax.html) - Comprehensive syntax guide with examples (PHP version).

## Community

- [GitHub Discussions](https://github.com/jgm/djot/discussions) - Official discussion forum for Djot.
- [GitHub Issues](https://github.com/jgm/djot/issues) - Report bugs and request features.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
