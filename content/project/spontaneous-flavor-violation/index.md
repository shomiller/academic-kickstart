+++
title = "Spontaneous Flavor Violation"
date = 2019-03-25T15:30:19-04:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = []

# Project summary to display on homepage.
summary = ""

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
# links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

In the Standard Model, Flavor-Changing Neutral Currents (FCNCs) are strongly suppressed by a combination of small Yukawa couplings, small CKM matrix elements, and the GIM mechanism. Precise measurements of these processes put tight constraints on the structure of new physics coupled to quarks. These constraints are typically avoided by assuming that new interactions are either "flavor-blind" or have a structure very similar to the standard model (thus inheriting some of the aforementioned protections). While these assumptions allow new physics at the TeV scale, they also necessitate that the new physics be coupled primarily to the heaviest generation of quarks, seriously limiting the phenomenology at high energy experiments.

{{< figure library="1" src="mirror-quark.png" title="The diagram leading to the SFV texture in one possible UV completion." width="400" >}}

Recently, I've been working with Daniel Egana-Ugrinovic and Patrick Meade on understanding different classes of "flavor vacua", i.e., the patterns of quark couplings in models of new physics. In doing so, we've engineered a new Ansatz called _Spontaneous Flavor Violation_ (SFV). This setup allows new interactions with sizable couplings to light quarks while still being safe from stringent constraints on FCNCs. In the context of particular models, e.g., a model with a second Higgs doublet, this leads to a number of novel signatures at colliders. For more details, check out our recent paper, and some preliminary results presented at a [GGI Workshop last August](https://www.ggi.infn.it/showevent.pl?id=270).
