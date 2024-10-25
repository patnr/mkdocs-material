# Home page

## Other items

Here's some code:

```python title="not bubble_sort.py" linenums="1" hl_lines="2 3"
if parts[-1] == "__init__":
    parts = parts[:-1] or src.parts[-1:]
    if not parts:
        # we're in root pkg
        parts = src.parts[-1:] # (1)!
```

1. :man_raising_hand: I'm a code annotation! I can contain `code`, **formatted
    text**, images, ... basically anything that can be written in Markdown.
