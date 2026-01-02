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
- [Footnote](#footnote)
- [Alert](#alert)
- [Comment](#comment)
- [Ignore](#ignore)
- [Table](#table)
- [Collapsed Section](#collapsed-section)
- [Diagram](#diagram)

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

[See Link](#link)

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

<br/>

# Footnote

**Input:** 

Reference \[\^1\]

\[\^1\]\: Footnote

<br/>

**Output:**

Reference [^1]

[^1]: Footnote

<br/>

# Alert

\> [!NOTE]\
\> Description

\> [!TIP]\
\> Description

\> [!IMPORTANT]\
\> Description

\> [!WARNING]\
\> Warning

\> [!CAUTION]\
\> Caution

<br/>

> [!NOTE]
> Description

> [!TIP]
> Description

> [!IMPORTANT]
> Description

> [!WARNING]
> Description

> [!CAUTION]
> Description

<br/>

# Comment

> **Use `<!-- Comment -->`**

</br>

# Ignore

> **Use `\`**

</br>

# Table

**Input:**

\| Header \| Header \|\
\| --- \| --- \|\
\| Cell \| Cell \|

\| Left Aligned \| Center Aligned \| Right Aligned \|\
\| :--- \| :---: \| ---: \|\
\| Left \| Center \| Right \|

<br/>

**Output:**

| Header | Header |
|---|---|
| Cell | Cell |

| Left Aligned | Center Aligned | Right Aligned |
| :--- | :---: | ---: |
| Left | Center | Right |

<br/>

# Collapsed Section

**Input:**

\<details\> 


\<summary\>Summary\<\/summary\>

Details

\<\/details\>

<br/>

**Output:**

<details>

<summary>Summary</summary>

Details

</details>

<br/>

# Diagrams

**Mermaid diagram:**

Input:

```
\```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
\```
```

Output:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

<br/>

**GeoJSON diagram:**

Input:

```
```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
}
```
```

Output:

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
}
```

<br/>

**TopoJSON diagram:**

Input:
```
```topojson
{
  "type": "Topology",
  "transform": {
    "scale": [0.0005000500050005, 0.00010001000100010001],
    "translate": [100, 0]
  },
  "objects": {
    "example": {
      "type": "GeometryCollection",
      "geometries": [
        {
          "type": "Point",
          "properties": {"prop0": "value0"},
          "coordinates": [4000, 5000]
        },
        {
          "type": "LineString",
          "properties": {"prop0": "value0", "prop1": 0},
          "arcs": [0]
        },
        {
          "type": "Polygon",
          "properties": {"prop0": "value0",
            "prop1": {"this": "that"}
          },
          "arcs": [[1]]
        }
      ]
    }
  },
  "arcs": [[[4000, 0], [1999, 9999], [2000, -9999], [2000, 9999]],[[0, 0], [0, 9999], [2000, 0], [0, -9999], [-2000, 0]]]
}
```
```

Output:

```topojson
{
  "type": "Topology",
  "transform": {
    "scale": [0.0005000500050005, 0.00010001000100010001],
    "translate": [100, 0]
  },
  "objects": {
    "example": {
      "type": "GeometryCollection",
      "geometries": [
        {
          "type": "Point",
          "properties": {"prop0": "value0"},
          "coordinates": [4000, 5000]
        },
        {
          "type": "LineString",
          "properties": {"prop0": "value0", "prop1": 0},
          "arcs": [0]
        },
        {
          "type": "Polygon",
          "properties": {"prop0": "value0",
            "prop1": {"this": "that"}
          },
          "arcs": [[1]]
        }
      ]
    }
  },
  "arcs": [[[4000, 0], [1999, 9999], [2000, -9999], [2000, 9999]],[[0, 0], [0, 9999], [2000, 0], [0, -9999], [-2000, 0]]]
}
```

<br/>

**STL 3D Diagram:**

Input:

```
```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```
```

Output:

```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```

