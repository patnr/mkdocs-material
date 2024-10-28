---
title: Demo
---

# Demonstration of markdown extensions


!!! info

    The markup possibilities are truly impressive.
    The built-in ones are documented [here](https://squidfunk.github.io/mkdocs-material/reference/icons-emojis/).

### Code

```python title="not bubble_sort.py" linenums="1" hl_lines="2 3"
if parts[-1] == "__init__":
    parts = parts[:-1] or src.parts[-1:]
    if not parts:
        # we're in root pkg
        parts = src.parts[-1:] # (1)!
```

1. :man_raising_hand: I'm a code annotation! I can contain `code`, **formatted
    text**, images, ... basically anything that can be written in Markdown.

### Math

$$
\operatorname{key} f=\{g\in G:f(g)=e_{H}\}{\mbox{.}}
$$

What about $a = b$


### Images


![Image title](https://dummyimage.com/600x400/eee/aaa){ align=right }

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.


With caption:

<figure markdown>
  ![Image title](https://dummyimage.com/600x400/){ width="300" }
  <figcaption>Image caption</figcaption>
</figure>
