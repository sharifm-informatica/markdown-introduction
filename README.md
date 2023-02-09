# Markdown Templates and Introduction

Arabic and English Markdown templates for professional and simple academic documents with YAML front matter.
This repo contains simple Arabic and English markdown templates useful in many applications and use cases.

The templates are free to use and adapt as you see fit.

The repo also has an example document with content explaining markdown uses and different text forms, headings, lists, tables, ...

This is a companion repository for a Google Developer Group (GDGMena) YouTube livestream session. The recording can be found at [https://www.youtube.com/watch?v=-4OmPelYnfk&list=PLlqOXLg-GOqeJWNURJtQKBWW6IQJKu9Ly&index=22](https://www.youtube.com/watch?v=-4OmPelYnfk&list=PLlqOXLg-GOqeJWNURJtQKBWW6IQJKu9Ly&index=22)

# Recommended Tools

Here we will list recommended tools for working with Markdown.

## Popular Markdown Editors on all Operating Systems

This is a bulleted list of Markdown editors:

- Mac: MacDown, iA Writer, or Marked 2
- iOS / Android: iA Writer
- Windows: ghostwriter or Markdown Monster
- Linux: ReText or ghostwriter
- Web: Dillinger or StackEdit

## Document Converter

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
