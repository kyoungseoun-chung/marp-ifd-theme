---
marp: true
title: Test marp slide
author: Author
paginate: true
_paginate: false
# header: <div class="wrapper"><div class="eth-logo"><img src="./assets/eth_logo_kurz_pos.svg"></div><div class="ifd-logo">Institute of Fluid Dynamics</div>
header: ![w:150](./assets/eth_logo_kurz_pos.svg) Institute of Fluid Dynamics
footer: Author
theme: marp_ifd_theme
---


<!-- _class: title -->

# This is a title
## - This is a sub title

<!-- Author need to be defined in h3 -->
### Author

---

## This is a sub-title

### This is a sub-sub-title

A normal paragraph

- `ul` element
  - `ul` element

1. `ol` element
2. `ol` element

---

## Insert an image below

- Metadata for Marp slide file
  - `marp: true` enables Marp slide
  - Image can be added using Markdown syntax:
    - If you place an image in the center of the slide, use `center` keyword.
    - Width and height can be adjusted with `w` and `h` keyword. Use `px` unit.
    - `![w:700 center](./assets/markdown_meta.png)`

![w:700 center](./assets/markdown_meta.png)

---

## Insert an image right

- Metadata for Marp slide file
  - `marp: true` enables Marp slide
  - Image can be added using Markdown syntax:
    - e.g. The image on the right-hand-side is added by:
    - `![bg right:50% 80%](./assets/markdown_meta.png)`

![bg right:50% 80%](./assets/markdown_meta.png)
