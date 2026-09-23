---
title: "Your post title"
description: "One sentence. It appears under the title and on the Blog page."
tags: [Climate]
# image: /assets/img/posts/your-cover.jpg
# image_caption: "Optional caption for the cover image"
# math: true
# published: false
---

Write your first paragraph here. Leave an empty line between paragraphs.

## A section heading

Normal text with a [link](https://example.com), **bold**, *italic*, and <mark>a highlighted phrase</mark>.

![Describe the image for people who can't see it](/assets/img/posts/example.svg)
*An optional caption, on the line right below the image.*

> A quote, or one idea you want to stand out.

- A bullet point
- Another bullet point

1. A numbered step
2. Another step

```python
import xarray as xr

ds = xr.open_dataset("era5.nc")
print(ds["t2m"].mean())
```

Inline code looks like `this`. With `math: true` above, write equations like $$E = mc^2$$.

A sentence with a footnote.[^1]

---

Three dashes on their own line (above) add a small divider.

[^1]: The footnote text appears at the end of the post.
