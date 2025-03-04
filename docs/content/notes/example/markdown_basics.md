## Markdown Basics

### Resources and Helpers

A nice cheat sheet about Markdown can be found at this link: <https://www.markdownguide.org/cheat-sheet/>.

On VS Code, there are some nice extensions that can help you write Markdown files:

- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) to provide useful shortcuts and commands
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) to properly format your Markdown files

Feel free to ask me if you have questions about Markdown.

### Comments

```markdown
This <!--This is a comment.--> is
<!--
Comments are not rendered.
They can take multiple lines
-->
a
sentence.
```

This <!--This is a comment.--> is
<!--
Comments are not rendered.
They can take multiple lines
-->
a
sentence.

### Headers

```markdown
<!-- Comment the fist headers to avoid messing up the outline of this file -->
<!--
# Level 1

## Level 2

### Level 3
-->

#### Level 4

##### Level 5

###### Level 6
```

<!--
# Level 1

## Level 2

### Level 3
-->

#### Level 4

##### Level 5

###### Level 6

### Bold and Italic

```markdown
- Normal text
- **Bold text**
- _Italic text_
- **_Bold and italic text_**
```

- Normal text
- **Bold text**
- _Italic text_
- **_Bold and italic text_**

### Lists

```markdown
Unordered list:

- Unordered list item 1
- Unordered list item 2
  - Nested unordered list item

Ordered list:

1. Ordered list item 1
2. Ordered list item 2
   1. Nested ordered list item
```

Unordered list:

- Unordered list item 1
- Unordered list item 2
  - Nested unordered list item

Ordered list:

1. Ordered list item 1
2. Ordered list item 2
   1. Nested ordered list item

### Links

```markdown
[Example link](https://www.example.com)
```

[Example link](https://www.example.com)

### Images

```markdown
![Example image](../../../images/example.jpg){ width="250" }
```

![Example image](../../../images/example.jpg){ width="250" }

### Blockquotes

```markdown
> This is a blockquote.
```

> This is a blockquote.

### Code

````markdown
Inline code: `print("Hello, World!")`

Code block:

```python
def hello_world():
    print("Hello, World!")
```
````

Inline code: `print("Hello, World!")`

Code block:

```python
def hello_world():
    print("Hello, World!")
```

### Tables

```markdown
Table: A simple table

| Header 1 | Header 2 |
| -------- | -------- |
| Cell 1   | Cell 2   |
| Cell 3   | Cell 4   |
```

Table: A simple table

| Header 1 | Header 2 |
| -------- | -------- |
| Cell 1   | Cell 2   |
| Cell 3   | Cell 4   |

### Math

```markdown
Inline math: $x^2$ is the square of $x$.

Block math:

$$
\int_0^\infty e^{-x^2} dx = \frac{\sqrt{\pi}}{2}
$$
```

Inline math: $x^2$ is the square of $x$.

Block math:

$$
\int_0^\infty e^{-x^2} dx = \frac{\sqrt{\pi}}{2}
$$
