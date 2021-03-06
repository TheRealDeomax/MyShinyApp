---
title: RMarkdown Primer
author: Prajuk Nusbaum
output: 
    html_document:
        number_sections: true
        toc: true
        toc_float:
            collapsed: false
            smooth_scroll: true
        code_download: true
        theme: united
        keep_md: true
---

# Level 1 Heading

This is a sentence.  Any text here gets rendered as normal text.

A blank line creates a new paragraph, still in the same section.

# Another Level 2 Heading

more text.

## Level 2 Heading

This is a subsection under the level 1 heading

# Back to Level 1

This starts a new section.

# Text Formating

_italic_

__bold__

___italic and bold ___

# Lists {#TheLists}

## Unordered Lits

- apples
- graps
- bananas
- oranges
- kiwis

## ordered Lists

### Numbered Lists

1. New York
1. New Jersey
1. Naples
1. Connecticut
1. Detroit

### Lettered Lists

a. Coal
a. Wood
a. Gas


## Nested Lists

1. New York
    a. Coal
    a. Wood
    a. Gas
        - Baker's Pride
        - Bari
    a. Electric
1. New Jersey
1. Philidelphia
1. Detroit


# Links

[My Website](www.jardedlander.com)

[Check out the pizza section](#TheLists)

# Math
$$
    \bar{x} = \sum_{i-1}^n \frac{x_i}{n}
$$
Inline equations look like $y = nx +b$.

# Footnotes

We^[Everyone is enjoying this video] are learning markdown^[markdown is a simple way of writing documents] on our way to learning R markdown.

