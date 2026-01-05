# GitHub Markdown Guide

A comprehensive minimal guide for markdown on GitHub. Keep this handy for quick reference.

# Table of Contents

- [Paragraph Text](#paragraph-text)
- [Heading Text](#heading-text)
- [Text Style](#text-style)
- [Quote](#quote)
- [Code](#code)
- [Link](#link)
- [Line Break](#line-break)
- [Image](#image)
- [List](#list)
- [Emoji](#emoji)
- [Footnote](#footnote)
- [Alert](#alert)
- [Comment](#comment)
- [Ignore Markdown](#ignore-markdown)
- [Table](#table)
- [Collapsed Section](#collapsed-section)
- [Diagrams](#diagrams)
- [Math](#math)
- [Quick Tips](#quick-tips)

# Paragraph Text

Use default text.

# Heading Text

Use `#` symbol.

**Code:**

```
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6
```

**Preview:**

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

# Text Style

| Style | Code | Preview |
|---|---|---|
| Bold | `**bold**` | **bold** |
| Italic | `*italic*` | *italic* |
| Strikethrough | `~~strikethrough~~` | ~strikethrough~ |
| Bold and italic | `***bold and italic***` | ***bold and italic*** |
| Subscript | `<sub\>subscript</sub>` | <sub>subscript</sub> |
| Superscript | `<sup\>superscript</sup>` | <sup>superscript</sup> |
| Underline | `<ins>underline</ins>` | <ins>underline</ins> |

# Quote

Use `>` symbol.

**Code:**

```
> Quote
```

**Preview:**

> Quote

# Code

Use `` ` `` symbol.

## Inline Code

**Code:**

````
`Inline code`
````

**Preview:**


`Inline code`

You can begin and end with two `` ` `` symbols to use `` ` `` in a code block.

## Block code

**Code:**

````
```python
print("Hello, World!")
```
````

**Preview:**

```python
print("Hello, World!")
```

You can specify the programming language.
You can begin and end with four `` ` `` symbols to use ```` ``` ```` in a code block.

# Link

Use `[ ]( )` symbols.

## Normal Link

**Code:**
```
[Google](https://www.google.com)
```

**Preview:**

[Google](https://www.google.com)

## Anchor Link

**Code:**

```
[Table of Contents](#table-of-contents)
```

**Preview:** 

[Table of Contents](#table-of-contents)

## Relative Link

**Code:**
```
[image.png](./image.png)
```

**Preview:**
[image.png](./image.png)

## Custom Anchor Link

**Code:**

```
[Custom Anchor Link](#custom-anchor-point)
```

**Preview:**

[Custom Anchor Link](#custom-anchor-point)

# Line Break

Use `\` or `<br/>`

**Code:**

```
Hello,\
World!

or

Bye, <br/> World!
```


**Preview:**

Hello,\
World!

or

Bye, <br/> World!

# Custom Anchor Point

```
<a name="custom-anchor-point"></a>
```

<a name="custom-anchor-point"></a>

# Image

Use `![ ]( )`

[See Link](#link)

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

**Use :emojicode:**

**Input:** `:smile:`

**Output:** :smile:

For more information check out: [Emoji List Unicode](https://github.com/Fantantonio/Emoji-List-Unicode)

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

**Use `<!-- Comment -->`**

**Input:**

```
The server update was <!-- NOT --> successful
```

**Output:**

The server update was <!-- NOT --> successful


# Ignore Markdown

To stop automatically formatting your text as markdown: 
**use `/` symbol** in front.

**Input:**

```
> Note
```

```
\> Note
```

**Output:**

> Note

\> Note

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

# Diagrams

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
````

*Output:*

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

**STL 3D Diagram:**

# Math

Use `$` symbol.

**Inline Math:**

*Input:*
```
$\sqrt{3x-1}+(1+x)^2$
```

*Output:*
$\sqrt{3x-1}+(1+x)^2$

**Math Block:**

*Input:*

```
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$
```

*Output:*

$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$

> [!NOTE]
> For more information visit: [Katex Documentation](https://katex.org/docs/supported.html)

# Quick Tips
