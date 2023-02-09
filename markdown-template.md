---
title: Advanced Markdown Template
subtitle: Stop Using Word Processors and Live Happily Ever After
author: Sharif M. Al Motawally, Informatica Information Systems Ltd.
thanks: I Thank GDGMena # acknowledgements and thanks to ...
date: \today
lang: en-UK
#lang: ar
#mainfont: Amiri
documentclass: report # article, report, book, letter, extarticle, extreport
classoptions:
  - a4paper
  - portrait
#geometry: # I do not recommend using this unless absolutely needed
#- top=2cm
#- left=1cm
#- right=1cm
#- bottom=2cm
toc: false
lof: false # List of Figures
lot: false # List of Tables
numbersections: false
linkcolor: Blue
fontsize: 14pt
---
# An Example Advanced Markdown Document

This is an example of a Markdown document with everything you need as an advanced Markdown user.

## Previous Videos in this Series

But First below is a list of previous videos in this series on the same channel:

- Introduction to Markdown [https://www.youtube.com/watch?v=TkaLDD0-JMA](https://www.youtube.com/watch?v=TkaLDD0-JMA)
- Complete playlist for programming and startups and cloud [https://www.youtube.com/playlist?list=PLlqOXLg-GOqeJWNURJtQKBWW6IQJKu9Ly](https://www.youtube.com/playlist?list=PLlqOXLg-GOqeJWNURJtQKBWW6IQJKu9Ly)

# In the Morning

This is an introduction to the stuff I do in the morning. This is the stuff I do in the morning. This is the stuff I do in the morning. This is the stuff I do in the morning. This is the stuff I do in the morning. This is the stuff I do in the morning. This is the stuff I do in the morning.

### Getting up

A subtitle for more stuff I do in the morning. A subtitle for more stuff I do in the morning. A subtitle for more stuff I do in the morning. A subtitle for more stuff I do in the morning. A subtitle for more stuff I do in the morning.

- Turn off alarm
- Get out of bed
- Exercise

### Breakfast

Breakfast is a very important meal. Breakfast is a very important meal. Breakfast is a very important meal. Breakfast is a very important meal. Breakfast is a very important meal. Breakfast is a very important meal.

- Eat eggs
- Drink Orange Juice
- Drink coffee

## In the evening

In the evening dinner then sleeping. In the evening dinner then sleeping. In the evening dinner then sleeping. In the evening dinner then sleeping. In the evening dinner then sleeping.

### Dinner

Meal choices for dinner are listed below. Meal choices for dinner are listed below. Meal choices for dinner are listed below.

- Eat spaghetti
- Drink Milk

### Going to sleep

Finally, we rest for a new day. Finally, we rest for a new day. Finally, we rest for a new day. Finally, we rest for a new day.

- Get in bed
- Count sheep
- Sleep

## What about documents with code

This is an example of a code block with automatic syntax highlighting. This is an example of a code block with automatic syntax highlighting. This is an example of a code block with automatic syntax highlighting. This is an example of a code block with automatic syntax highlighting.

```python
# Store input numbers
num1 = input('Enter first number: ')
num2 = input('Enter second number: ')

# Add two numbers
sum = float(num1) + float(num2)

# Display the sum
print('The sum of {0} and {1} is {2}'.format(num1, num2, sum))
```

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

## Can we do Tables Easily?

Yes we can. Yes we can. Yes we can. Yes we can. Yes we can. Yes we can. Yes we can. Yes we can:

 | test | description                       |
 |------|-----------------------------------|
 | test | This description is very long     |
 | test | another long long long description|

## Even easier tables with different alignment for each column?

Oh, yes we can. Yes we can. Yes we can. Yes we can. Yes we can. Yes we can. Yes we can. Yes we can. Yes we can. Yes we can. Yes we can:

  Right     Left     Center     Default
-------     ------ ----------   -------
     12     12        12            12
    123     123       123          123
      1     1          1             1

## Another Level 2 Heading

The Quick Brown fox jumps over. The Quick Brown fox jumps over. The Quick Brown fox jumps over. The Quick Brown fox jumps over. Thesdfsdfsdf Quick Brown fox jumps over. . The Quick Brown fox jumps over. The Quick Brown fox jumps over.

[This is a simple link to Google](https://google.com)

The Quick Brown fox jumps over. The Quick Brown fox jumps over. The dsfsdfsdfQuick Brown fox jumps over. The Quick Brown fox jumps over. The Quick Brown fox jumps over. The Quick Brown fox jumps over. The Quick Brown fox jumps over. The Quick Brown fox jumps over. The Quick Brown fox jumps over. The Quick Brown fox jumps over.

![This is the logo for the Go Language](../go-introduction-talk/intoduction-to-golang/images/appenginegophercolor.png)
