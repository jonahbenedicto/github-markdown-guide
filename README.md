# GitHub Markdown

A Comprehensive Guide to Markdown on GitHub.

<br/>

# Table of Contents

- [Paragraph](#paragraph)
- [Heading](#heading)
- [Style (Bold, Italic, Subscript, Superscript, Underline)](#style)
- [Quote](#quote)
- [Code](#code)
- [Link](#link)
- [Line break](#line-break)
- [Image](#image)
- [List](#list)
- [Emoji](#emoji)

<br/>

# Paragraph

> **Use default text**

<br/>

# Heading

> **Use `#` symbol:**

<br/>

**Input:**

\# Heading 1

\#\# Heading 2

\#\#\# Heading 3

\#\#\#\# Heading 4

\#\#\#\#\# Heading 5

\#\#\#\#\#\# Heading 6

<br/>

**Output:**

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6


<br/>

<br/>


# Style

| Style | Syntax | Keyboard Shortcut | Example | Output |
|---|---|---|---|---|
| Bold | `** **` or `__ __` | `Command`+`B` <br/> (Mac) <br/> or <br/> `Ctrl`+`B` <br/> (Windows/Linux) | This is <br/> \*\*bold\*\* <br/> text | This is <br/> **bold** <br/> text |
| Italic | `* *` or `_ _` | `Command`+`I` <br/> (Mac) <br/> or <br/> `Ctrl`+`I` <br/> (Windows/Linux) | This is <br/> \*italic\* <br/> text | This is <br/> *italic* <br/> text |
| Strikethrough | `~~ ~~` or `~ ~` | None | This is <br/> \~strikethrough\~ <br/> text | This is <br/> ~strikethrough~ <br/> text |
| Bold and italic | `*** ***` | None | This is <br/> \*\*\*bold and italic\*\*\* <br/> text | This is <br/> ***bold and italic*** <br/> text |
| Subscript | `<sub> </sub>` | None | This is <br/> \<sub\>subscript\<\/sub\> <br/> text | This is <br/> <sub>subscript</sub> <br/> text |
| Superscript | `<sup> </sup>` | None | This is <br/> \<sup\>superscript\<\/sup\> <br/> text | This is <br/> <sup>superscript</sup> <br/> text |
| Underline | `<ins> </ins>` | None | this is <br/> \<ins\>underline\<\/ins\> <br/> text | This is <br/> <ins>underline</ins> <br/> text |

<br/>

# Quote

> **Use `>` symbol:**

<br/>

**Input:**

\> Quote

<br/>

**Output:**

> Quote

# Code

> **Use `` ` `` symbol:**

<br/>

**Input:**

\`Inline code\`

\`\`\` <br/>
Block code <br/>
\`\`\`

\`\`\`python <br/>
Python block code <br/>
\`\`\`

<br/>

**Output:**

`Inline code`

```
Block code
```

```python
print("Python block code")
```

<br/>

# Link

> **Use \[Text\]\(URL\)**

<br/>

**Normal Link:**

Input: \[Google\]\(https://www.google.com\)

Output: [Google](https://www.google.com)

<br/>

**Heading Link:**

Input: \[Table of Contents\]\(#table-of-contents\)

Output: [Table of Contents](#table-of-contents)

<br/>

**Relative Link:**

<br/>

**Custom Anchor Link:**

Input: \[Custom Anchor Link\]\(#custom-anchor-point\)

Output: [Custom Anchor Link](#custom-anchor-point)

<br/>

# Line Break

> **Use `\` or `<br/>`**

<br/>

**Input:**

Hello, \\ World!

Bye, \<br\/\> World!

<br/>

**Output:**

Hello,\ World!

Bye, <br/> World!

<br/>

# Custom Anchor Point

\<a name="custom-anchor-point"\>\<\/a\>

<a name="custom-anchor-point"></a>

<br/>

# Image

> **Use \!\[Alternative Text\]\(URL\)**

<br/>

# List

**Unordered List:**

Input:

\- Item\
\* Item\
\+ Item

<br/>

Output:

- Item
* Item
+ Item

<br/>

**Sorted List:**

Input:

1\. Item\
2\. Item\
3\. Item

<br/>

Output:

1. Item
2. Item
3. Item

<br/>

**Nested List:**

Input:

\- Item \
&emsp; \- Item \
&emsp; &emsp; \- Item

<br/>

Output:
- Item
    - Item
        - Item

<br/>

**Task List:**

Input:

\- \[x\]\
\- \[ \]

<br/>

Output:

- [x] Task
- [ ] Task

<br/>

# Emoji

> **Use :emojicode:**

**Input:** `:smile:`

**Output:** :smile:


