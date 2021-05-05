# Atom packages guide (work in progress)

## Table of Content
- [Syntax](#syntax)
  - [Programming](#programming)
  - [Configuration](#configuration)
  - [Template](#template)
  - [Other](#other)
- [Lint](#lint)
- [Autocomplete](#autocomplete)
  - [Programming](#programming-autocomplete)
  - [Configuration](#configuration-autocomplete)
  - [Template](#template-autocomplete)
  - [Other](#other-autocomplete)
- [Other](#other)
  - [Editing](#editing)
  - [Navigation](#navigation)
  - [Visual](#visual)
  - [General](#general)
- [Themes](#themes)
  - [User interface](#user-interface)
  - [Syntax coloring](#syntax-coloring)

## Syntax
Language packages extend the editor with syntax highlighting and/or
snippets for a specific language or file format.

#### Programming
- [Haskell](https://atom.io/packages/language-haskell)
- [Julia](https://atom.io/packages/language-julia)
- [Elixir](https://github.com/elixir-editors/language-elixir)
- [Scala](https://atom.io/packages/language-scala)
- [Lua](https://github.com/Azganoth/language-lua-plus)
- [Fortran](https://atom.io/packages/language-fortran)
- [Tcl](https://atom.io/packages/language-dashtcl)
- [Awk](https://atom.io/packages/language-awk)
- [Sed](https://atom.io/packages/language-sed)
- [Powershell](https://atom.io/packages/language-powershell)
- [Batchfile](https://atom.io/packages/language-batchfile)
- [Oracle PL/SQL](https://github.com/OraOpenSource/language-oracle)
- [R](https://atom.io/packages/atom-language-r)
- [Matlab](https://github.com/thedavidprice/language-matlab-octave)
- [Purescript](https://atom.io/packages/language-purescript)
- [Common lisp](https://atom.io/packages/language-common-lisp)

#### Configuration
- [Ini](https://atom.io/packages/language-ini)
- [Dotenv](https://atom.io/packages/language-dotenv)
- [Dockerfile](https://atom.io/packages/language-docker)
- [Nginx](https://atom.io/packages/language-nginx)
- [Apache](https://atom.io/packages/language-apache)
- [Htaccess](https://atom.io/packages/language-htaccess)
- [Ansible](https://atom.io/packages/language-ansible)
- [Terraform](https://atom.io/packages/language-terraform)
- [Cmake](https://atom.io/packages/language-cmake-2)

#### Template
- [Pug/Jade](https://atom.io/packages/language-pug-jade)
- [Twig](https://atom.io/packages/atom-twig)
- [Vue](https://atom.io/packages/language-vue)
- [Blade](https://atom.io/packages/language-blade)
- [Slim](https://atom.io/packages/language-slim)
- [Haml](https://atom.io/packages/language-haml)

#### Other
- [Latex](https://github.com/ashthespy/Atom-LaTeX)
- [Asciidoc](https://atom.io/packages/language-asciidoc)
- [Stylus](https://atom.io/packages/stylus)
- [Graphql](https://atom.io/packages/language-graphql)

## Lint
List of all kind of checkers (syntax, style, spelling etc) at
[https://atomlinter.github.io](https://atomlinter.github.io).
Most of the [autocomplete](#autocomplete) packages provides linting as well.

## Autocomplete
Autocomplete, navigation (go to definition, find usages etc), linting.
#### Programming
- [Typescript](https://atom.io/packages/atom-typescript)
- [Javascript](https://atom.io/packages/atom-typescript) (Follow https://github.com/TypeStrong/atom-typescript/blob/master/docs/faq.md#i-want-to-use-atom-typescript-with-javascript-too)
- PHP - [intelephense](https://atom.io/packages/ide-intelephense) (Not open source), [serenata](https://atom.io/packages/php-ide-serenata)
- [Elixir](https://atom.io/packages/ide-elixir)
- [Bash](https://atom.io/packages/ide-bash)
- [R](https://atom.io/packages/ide-r)
- Go - [ide-go](https://github.com/ckaznocha/ide-go), [ide-gopls](https://atom.io/packages/ide-gopls), [atom-ide-golang](https://atom.io/packages/atom-ide-golang)
- [Purescript](https://atom.io/packages/ide-purescript)
- [Common lisp](https://atom.io/packages/slima)

#### Configuration

#### Template
- [Vue](https://atom.io/packages/atom-ide-vue)
#### Other
- [Latex](https://github.com/ashthespy/Atom-LaTeX)

## Other
#### Editing
- [Beautify](https://atom.io/packages/atom-beautify)
Format code with many languages support.

- [Sublime style column selection](https://atom.io/packages/sublime-style-column-selection)
Select column (block select).

- [Docblockr](https://atom.io/packages/docblockr)
Documentation comment writing helper for jsdoc, phpdoc etc.

- [Sort Lines](https://atom.io/packages/sort-lines)
Sorts your lines. Never gets tired.

- [Toggle Quotes](https://atom.io/packages/toggle-quotes)
Quickly toggle between single and double quotes.

- [Clipboard plus](https://atom.io/packages/clipboard-plus)
Copy/cut history with fuzzy select to insert.

- [Expand region](https://atom.io/packages/expand-region)
Expanding selection.

- [Emmet](https://atom.io/packages/emmet)
Emmet integration. (For web developers)

#### Navigation
- [Advanced Open File](https://atom.io/packages/advanced-open-file)
Fast open/create file from current directory. Also fast go to system (type '/') or home directory (type '~/').

- [Jumpy](https://atom.io/packages/jumpy)
Quickly jump around visible text.

- [Center line](https://atom.io/packages/center-line)
Center editor on current line or align to top or bottom.

- [Cursor history](https://atom.io/packages/cursor-history)
Jump back/forward.

- [Recent files fuzzy finder](https://atom.io/packages/recent-files-fuzzy-finder)
Fuzzy open recent files.

#### Visual
- [File Icons](https://atom.io/packages/file-icons)
Adds file specific icons to Tree View, Fuzzy Finder and optionally tabs.

- [Pigments](https://atom.io/packages/pigments)
A package to display colors in project and files.

- [Minimap](https://atom.io/packages/minimap)
A preview of the full source code.

- [Highlight selected](https://atom.io/packages/highlight-selected)
Highlight selected word.

#### General
- [Sync Settings](https://atom.io/packages/sync-settings)
Synchronize package settings, keymap and installed packages across Atom instances.

- [PlatformIO IDE Terminal](https://atom.io/packages/platformio-ide-terminal)
A terminal package for Atom.

- [Git plus](https://atom.io/packages/git-plus)
Git integration.

- [Script](https://atom.io/packages/script)
Run scripts based on file name, a selection of code, or by line number with many languages support.

- [Indent detective](https://atom.io/packages/indent-detective)
Detect and set editor indentation automatically.

- [Editor Config](https://atom.io/packages/editorconfig)
[EditorConfig](https://editorconfig.org) integration.

- [Fonts](https://atom.io/packages/fonts)
Lots of monospace fonts.

- [Color Picker](https://atom.io/packages/color-picker)
Color picker that supports HEX, HEXa, RGB, RGBa, HSL, HSLa, HSV, HSVa, VEC3, VEC4 – and is able to convert between the formats.

## Themes
Built in themes not listed.
### Dark
#### User interface
- [Seti](https://atom.io/themes/seti-ui)
- [Material](https://atom.io/themes/atom-material-ui)
- [Nord](https://atom.io/themes/nord-atom-ui)

#### Syntax coloring
- [Monokai](https://atom.io/themes/monokai)
- [Dracula](https://atom.io/themes/dracula-syntax)
- [Seti](https://atom.io/themes/seti-syntax)
- [Pure](https://atom.io/themes/pure-syntax)
- [Material](https://atom.io/themes/atom-material-syntax)
- [Nord](https://atom.io/themes/nord-atom-syntax)
- [Chester](https://github.com/csutter/chester-atom-syntax)
- [Gruvbox](https://atom.io/themes/gruvbox-plus-syntax)

### Light
#### User interface
- [Material](https://atom.io/themes/atom-material-ui)
- [Native](https://atom.io/themes/native-ui)

#### Syntax coloring
- [Material](https://atom.io/themes/atom-material-syntax)
- [Eclipse](https://atom.io/themes/atom-eclipse-syntax)
- [Gruvbox](https://atom.io/themes/gruvbox-plus-syntax)
- [Pure](https://atom.io/themes/pure-light-syntax)
