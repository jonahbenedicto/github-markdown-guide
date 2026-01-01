# GitHub Markdown

A Comprehensive Guide to Markdown on GitHub.

# Table of Contents

- [Paragraph](#paragraph)
- [Heading](#heading)
- [Style (Bold, Italic, Subscript, Superscript, Underline)](#style)
- [Quote](#quote)
- [Code](#code)
- [Link](#link)
- [Line break](#line-break)

# Paragraph

Default

# Heading

> [!NOTE]
> Use `#` symbol

\# Heading 1

\#\# Heading 2

\#\#\# Heading 3

\#\#\#\# Heading 4

\#\#\#\#\# Heading 5

\#\#\#\#\#\# Heading 6

> [!NOTE]
> Preview

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

> [!Note]
> Additional

A table of contents is automatically added when you use two or more headings.

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

# Quote

Use `>` symbol

\> Quote

---

> Quote

# Code

Use `` ` `` symbol

\`Inline code\`

\`\`\` <br/>
Block code <br/>
\`\`\`

\`\`\`python <br/>
Python block code <br/>
\`\`\`

---

`Inline code`

```
Block code
```

```python
print("Python block code")
```

# Link

Use \[Text\]\(URL\)

**Normal Link:**

\[Google\]\(https://www.google.com\)

[Google](https://www.google.com)

**Heading Link:**

\[Table of Contents\]\(#table-of-contents\)

[Table of Contents](#table-of-contents)

**Relative Link:**

**Custom Anchor Link:**
\[Custom Anchor Link\]\(#custom-anchor-point\)

[Custom Anchor Link](#custom-anchor-point)

# Custom Anchor Point

\<a name="custom-anchor-point"\>\<\/a\>

<a name="custom-anchor-point"></a>

# Line Break

Use `\` or `<br/>`

Hello, \\ World!

Bye, \<br\/\> World!

---

Hello,\ World!

Bye, <br/> World!

