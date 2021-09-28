---
title: AdaptiveResonance.jl
subtitle: A Julia package for Adaptive Resonance Theory (ART) modules.
date: 2019-07-29
authors: ["admin"]
categories: ["projects"]
tags: ["Julia", "ART"]
summary: A Julia package for Adaptive Resonance Theory (ART) modules.
featured: true
# profile: true
# commentable: true
# share: true

# Link this post with a project
projects: ["AdaptiveResonance.jl"]

header:
    # image: headers/bubbles-wide.jpg
    image: path.jpg
    caption: "Image credit:  [**Academic**](https://github.com/gcushen/hugo-academic/)"

# Featured image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
image:
  placement: 1
  caption: "ART Module Architecture"
  # focal_point: "Center"
  focal_point: "TopLeft"
  preview_only: false
---

`AdaptiveResonance.jl` is a registered JuliaHub package for Adaptive Resonance Theory (ART) modules.
These algorithms are built upon a foundation of the neural theory and implementations of Stephen Grossberg and Gail Carpenter.

<!-- KaTeX can be used to generate complex math formulas. It supports in-line math using the `\\( ... \\)` delimiters, like this: \\( E = mc^2 \\). By default, it does *not* support in-line delimiters `$...$` because those occur too commonly in typical webpages. It supports displayed math using the `$$` or `\\[...\\]` delimiters, like this:

Formula 1:
$$
\phi = \frac{(1+\sqrt{5})}{2} = 1.6180339887\cdots
$$

Formula 2: (same formula, different delimiter)
\\[
\phi = \frac{(1+\sqrt{5})}{2} = 1.6180339887\cdots
\\]

Additional details can be found on [GitHub](https://github.com/Khan/KaTeX) or on the [Wiki](http://tiddlywiki.com/plugins/tiddlywiki/katex/).
more

### Example 1

If the text between $$ contains newlines it will rendered in display mode:
```
$$
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
$$
```
$$
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
$$


### Example 2
```
$$
\frac{1}{\Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{\frac25 \pi}} = 1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {1+\frac{e^{-6\pi}} {1+\frac{e^{-8\pi}} {1+\cdots} } } }
$$
```
$$
\frac{1}{\Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{\frac25 \pi}} = 1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {1+\frac{e^{-6\pi}} {1+\frac{e^{-8\pi}} {1+\cdots} } } }
$$


### Example 3
```
$$
1 +  \frac{q^2}{(1-q)}+\frac{q^6}{(1-q)(1-q^2)}+\cdots = \prod_{j=0}^{\infty}\frac{1}{(1-q^{5j+2})(1-q^{5j+3})}, \quad\quad \text{for }\lvert q\rvert<1.
$$
```
$$
1 +  \frac{q^2}{(1-q)}+\frac{q^6}{(1-q)(1-q^2)}+\cdots = \prod_{j=0}^{\infty}\frac{1}{(1-q^{5j+2})(1-q^{5j+3})}, \quad\quad \text{for }\lvert q\rvert<1.
$$

### Example 4

Remember, certain characters are rendered by markdown, so you may need to workaround those issues. You can find the complete list of KaTeX supported functions here: [https://khan.github.io/KaTeX/docs/supported.html](https://khan.github.io/KaTeX/docs/supported.html)

For example, the `'` character can  be replaced with `^\prime`:

$$
G^\prime = G - u
$$

The `"` character can  be replaced with `^{\prime\prime}`:

$$
G^{\prime\prime} = G^\prime - v
$$ -->
