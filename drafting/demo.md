+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 15  # Order that this section will appear.

title = "λόγος"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"

  # Background gradient.
  # gradient_start = "DarkGreen"
  # gradient_end = "ForestGreen"

  # Background image.
  # image = "headers/bubbles-wide.jpg"  # Name of image in `static/img/`.
  image = "headers/beach.jpg"  # Name of image in `static/img/`.
  image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[cta]
  url = "https://sourcethemes.com/academic/docs/install/"
  label = "Get Started"
  icon_pack = "fas"
  icon = "download"

[advanced]
 # Custom CSS.
 css_style = ""

 # CSS class.
 css_class = ""
+++

asdfasdfasdf!

{{% callout note %}}
Quickly discover relevant content by [filtering publications]({{< ref "/post/_index.md" >}}).
{{% /callout %}}

  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0

  [[content.filter_button]]
    name = "All"
    tag = "*"

  [[content.filter_button]]
    name = "Philosophy"
    tag = "philosophy"

  [[content.filter_button]]
    name = "Filtering"
    tag = "filtering"

      [[content.filter_button]]
    name = "Philosophy"
    tag = "philosophy"

  [[content.filter_button]]
    name = "Filtering"
    tag = "filtering"


      # Filter posts by a taxonomy term.
  [[content.filters]]
    tag = ""
    category = ""
    publication_type = ""
    exclude_featured = false




**The Best Way to Create the Website You Want from Markdown (or Jupyter/RStudio)**

Build **Anything** with Widgets

<span style="text-shadow: none;"><a class="github-button" href="https://github.com/gcushen/hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star this on GitHub">Star</a><script async defer src="https://buttons.github.io/buttons.js"></script></span>

stuff and things {{< ref "/post/2019-07-29-logos/index.md" >}}
