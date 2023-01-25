# Marp ETHZ-IFD theme

ETHZ-IFD theme for the [Marp](https://marp.app) presentation.

The theme inherits from the default Marp theme, however logos have been added to the header, as well as a title page.

It is recommended that you use VScode for editing.

## How to use

Install Marp tools

```bash
brew install marp-cli
# or
npm i @marp-team/marp-cli
```

Once you install `marp-cli`, clone this repository and create `slides` folder inside.

```bash
git clone git@github.com:kyoungseoun-chung/marp-ifd-theme.git
cd marp-ifd-theme
mkdir slides
cd slides
```

And create slide markdown files and add metadata as follows:

```Markdown
---
marp: true
title: Test marp slide
author: Author
paginate: true
_paginate: false
header: ![w:150](../assets/eth_logo_kurz_pos.svg) Institute of Fluid Dynamics
footer: Author
theme: marp_ifd_theme
---
```

Now, you can run `marp-cli` using `-p` and `-s` flag to enable preview and server.

```bash
marp -p -s --theme theme-dir ./
```

Alternatively, you can use VScode for preview and editing.

Due to `.vscode/settings.json` file, VScode will automatically recognize theme file. Therefore, no need of extra actions if you already downloaded the [Marp plugin](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode).

## Demo

Using `marp-cli`:

![demo1](assets/screenshot_2.png)

Using VScode:
![demo2](assets/screenshot.png)
