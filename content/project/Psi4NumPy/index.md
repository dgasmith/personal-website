+++
title = "Psi4NumPy"
date = 2018-12-15T15:47:31-05:00
draft = false

# share = false  # Show social sharing links?
profile = false  # Show author profile?
comments = false  # Show comments?

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Quantum Chemistry", "C", "Python"]

# Project summary to display on homepage.
summary = "The overall goal of the Psi4NumPy project is to provide an interactive quantum chemistry framework for reference implementations, rapid prototyping, development, and education."

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Links (optional).
url_pdf = ""
url_code = ""
url_dataset = ""
url_slides = ""
url_video = ""
url_poster = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++


> What I cannot create, I do not understand. - Richard Feynman

The overall goal of the [Psi4NumPy](https://github.com/psi4/psi4numpy)
 project is to provide an interactive quantum
chemistry framework for reference implementations, rapid prototyping,
development, and education. To do this, quantities relevant to quantum
chemistry are computed with the Psi4 electronic structure package, and
subsequently manipulated using the Numerical Python (NumPy) package. This
combination provides an interface that is both simple to use and remains
relatively fast to execute.


```python
import psi4

mol = psi4.geometry("He")
```
