# Markdown Templates and Introduction

This repository contains [Arabic](./arabic-markdown-template.md) and [English](markdown-template.md) Markdown templates for professional and academic documents with simple YAML front matter. These templates make use of markdown extensions and LaTeX typesetting engines in [Pandoc](https://pandoc.org/) to make simple documents much more professional and easily adaptable to many use cases. The templates are free to use and adapt.

The repo also has an [example document](example-simple-markdown-document.md) with content demonstrating and explaining markdown's different text forms, headings, lists, tables, ...

This is a companion repository for a Google Developer Group (GDGMena) YouTube livestream session. The video can be found at [Advanced Markdown ماركداون :مستندات ووثائق جميلة سهلة 2](https://www.youtube.com/watch?v=-4OmPelYnfk). It explains all parts of the templates and examples in the Arabic language.

[![Advanced Markdown ماركداون :مستندات ووثائق جميلة سهلة 2](https://img.youtube.com/vi/-4OmPelYnfk/0.jpg)](https://www.youtube.com/watch?v=-4OmPelYnfk)

# Recommended Tools

Here we will list recommended tools for working with Markdown.

## Popular Markdown Editors on all Operating Systems

This is a bulleted list of Markdown editors:

- Windows: ghostwriter or Markdown Monster
- Mac: MacDown, iA Writer, or Marked 2
- Linux: ReText or ghostwriter
- iOS / Android: iA Writer
- Web: Dillinger or StackEdit

## [Pandoc](https://pandoc.org/): the Great Document Converter

The king of document converters and a very powerful tool on its own is [Pandoc](https://pandoc.org/). You can download it from [https://pandoc.org/](https://pandoc.org/).

Pandoc usage is easy:

```shell
pandoc -s sourceFile.md -o outputFile.pdf
```

For converting Arabic documents we recommend using the following option

```shell
pandoc -s --pdf-engine=lualatex sourceFile.md -o outputFile.pdf
```

You can simply change the outputFile extension for other file formats like

- .doc
- .docx
- .html
- .odt

Many other formats are supported. You can also convert from these formats to Markdown and to each other using pandoc by simply changing the sourceFile extension.

### My Favourite Editors

This is a numbered list of my favourite Markdown editors:

1. Visual Studio Code for English and for developers
1. Ghostwriter: for Arabic and non developers

### Recommended VSCode Extensions

With visual Studio Code the following extensions are highly recommended:

- [vscode-pandoc](https://marketplace.visualstudio.com/items?itemName=ChrisChinchilla.vscode-pandoc)
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
- [LanguageTool Linter](https://marketplace.visualstudio.com/items?itemName=davidlday.languagetool-linter)
