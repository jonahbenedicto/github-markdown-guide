# GitHub Markdown

A Comprehensive Guide to Markdown on GitHub.

# Table of Contents

- [Paragraph](#paragraph)
- [Heading](#heading)
- [Format Text (Bold, Italic, Subscript, Superscript, Underline)](#format-text)
- [Quote](#quote)
- [Code](#code)
- [Link](#link)
- [Line break](#line-break)
- [Image](#image)
- [List (Unordered List, Ordered List)](#list)
- [Emoji](#emoji)
- [Footnote](#footnote)
- [Alert (Note, Tip, Important, Warning, Caution)](#alert)
- [Comment](#comment)
- [Ignore Markdown Format](#ignore-markdown-format)
- [Table](#table)
- [Collapsed Section](#collapsed-section)
- [Diagram (Mermaid, GeoJSON, TopoJSON, STL 3D](#diagram)
- [Math](#math)

# Paragraph Text

Use default text.

# Heading Text

Use `#` symbol.

**Input:**

```
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6
```

<br/>

**Output:**

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

# Format Text

| Format | Syntax | Input | Output |
|---|---|---|---|
| Bold | `** **` | `**bold**` | **bold** |
| Italic | `* *` | `*italic*` | *italic* |
| Strikethrough | `~~ ~~` | `~~strikethrough~~` | ~strikethrough~ |
| Bold and italic | `*** ***` | `***bold and italic***` | ***bold and italic*** |
| Subscript | `<sub> </sub>` | `<sub\>subscript</sub>` | <sub>subscript</sub> |
| Superscript | `<sup> </sup>` | `<sup\>superscript</sup>` | <sup>superscript</sup> |
| Underline | `<ins> </ins>` | `<ins>underline</ins>` | <ins>underline</ins> |

# Quote

Use `>` symbol.

**Input:**

```
> Quote
```

**Output:**

> Quote

# Code

Use `` ` `` symbol.

**Input:**

````
`Inline code`
````

````
```
Block code
```
````

`````
````
Code with back ticks
````
`````

````
```python
print("Hello, World!")
```
````

**Output:**

`Inline code`

```
Block code
```

````
```
Code with backticks
```
````

```python
print("Hello, World!")
```

# Link

Use `[ ]( )`.

**Normal Link:**

*Input:*
```
[Google](https://www.google.com)
```

*Output:*

[Google](https://www.google.com)

**Heading Link:**

*Input:*

```
[Table of Contents](#table-of-contents)
```

*Output:* 

[Table of Contents](#table-of-contents)

**Relative Link:**


**Custom Anchor Link:**

*Input:*

```
[Custom Anchor Link](#custom-anchor-point)

```

*Output:*

[Custom Anchor Link](#custom-anchor-point)

# Line Break

Use `\` or `<br/>`

**Input:**

```
Hello,\
World!
```

```
Bye, <br/> World!
```

**Output:**

Hello,\
World!

Bye, <br/> World!

# Custom Anchor Point

```
<a name="custom-anchor-point"></a>
```

<a name="custom-anchor-point"></a>

# Image

Use `![ ]( )`

# List

**Unordered List:**

*Input:*

```
- Item
* Item
+ Item
```

*Output:*

- Item
* Item
+ Item

**Sorted List:**

*Input:*

```
1. Item
2. Item
3. Item
```

*Output:*

1. Item
2. Item
3. Item

**Nested List:**

*Input:*

```
- Item
    - Item
        - Item
```

*Output:*

- Item
    - Item
        - Item

**Task List:**

*Input:*

```
- [x] Task
- [ ] Task
```

*Output:*

- [x] Task
- [ ] Task

# Emoji

> **Use :emojicode:**

**Input:** `:smile:`

**Output:** :smile:

# Footnote

**Input:** 

```
Reference [^1]

[^1]: Footnote
```

**Output:**

Reference [^1]

[^1]: Footnote

# Alert

**Input:**

```
> [!NOTE]
> Description
```

```
> [!TIP]
> Description
```

```
> [!IMPORTANT]
> Description
```

```
> [!WARNING]
> Description
```

```
> [!CAUTION]
> Description
```

**Output:**

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

# Comment

> **Use `<!-- Comment -->`**

# Ignore Markdown Format

> **Use `\`**

# Table

**Input:**

```
| Header | Header |
| --- | --- |
| Cell | Cell |

| Left Aligned | Center Aligned | Right Aligned |
| :--- | :---: | ---: |
| Left | Center | Right |
```

**Output:**

| Header | Header |
|---|---|
| Cell | Cell |

| Left Aligned | Center Aligned | Right Aligned |
| :--- | :---: | ---: |
| Left | Center | Right |

# Collapsed Section

**Input:**

```
<details> 
<summary>Summary</summary>
Details
</details>
```

**Output:**

<details>
<summary>Summary</summary>
Details
</details>

# Diagram

**Mermaid diagram:**

*Input:*

````
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
````

*Output:*

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

**GeoJSON diagram:**

*Input:*

````
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
````

*Output:*

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

**TopoJSON diagram:**

*Input:*
````
```topojson
{
  "type": "Topology",
  "objects": {
    "example": {
      "type": "GeometryCollection",
      "geometries": [
        {
          "type": "Point",
          "coordinates": [4000, 5000]
        },
        {
          "type": "LineString",
          "arcs": [0]
        },
        {
          "type": "Polygon",
          "arcs": [[1]]
        }
      ]
    }
  },
  "arcs": [
    [[4000, 0], [1999, 9999], [2000, -9999], [2000, 9999]],
    [[0, 0], [0, 9999], [2000, 0], [0, -9999], [-2000, 0]]
  ]
}
```
````

*Output:*

```topojson
{
  "type": "Topology",
  "objects": {
    "example": {
      "type": "GeometryCollection",
      "geometries": [
        {
          "type": "Point",
          "coordinates": [4000, 5000]
        },
        {
          "type": "LineString",
          "arcs": [0]
        },
        {
          "type": "Polygon",
          "arcs": [[1]]
        }
      ]
    }
  },
  "arcs": [
    [[4000, 0], [1999, 9999], [2000, -9999], [2000, 9999]],
    [[0, 0], [0, 9999], [2000, 0], [0, -9999], [-2000, 0]]
  ]
}
```

**STL 3D Diagram:**

*Input:*

````
```stl
solid cube_corner
  facet normal 0 0 -1
    outer loop
      vertex 0 0 0
      vertex 1 0 0
      vertex 0 1 0
    endloop
  endfacet
endsolid
```
````

*Output:*

```stl
solid cube_corner
  facet normal 0 0 -1
    outer loop
      vertex 0 0 0
      vertex 1 0 0
      vertex 0 1 0
    endloop
  endfacet
endsolid
```

# Math

Use `$` symbol.

**Inline Math:**

*Input:*
```
$\sqrt{3x-1}+(1+x)^2$
```

*Output:*
$\sqrt{3x-1}+(1+x)^2$

**Math Block: **

*Input:*

```
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$
```

*Output:*

$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$



