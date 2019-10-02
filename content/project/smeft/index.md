+++
title = "Standard Model EFT"
date = 2019-03-25T15:31:06-04:00
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

One way of parameterizing new physics beyond the Standard Model in a model-agnostic way is to use Effective Field Theory techniques in the so-called "Standard Model Effective Field Theory", or SMEFT.
In the SMEFT, the new physics is treated using higher-dimension operators of Standard Model fields, which lead to deviations in both the coupling strength and the kinematics of interactions between Standard Model particles which one can hope to measure at colliders.
The most effective way of measuring the effects of these new operators is by measuring not only the rates of different rare processes at the LHC, but also the kinematic distributions in these processes.

One direction in my research is to understand how best to make these differential measurements. To do this, we use machine learning techniques, implemented in the package [MadMiner](https://github.com/diana-hep/madminer) to compute quantities closely related to the "Optimal Observables" which have been used in various applications for years. These observables help us understand the best limits we can obtain on theory parameters given the data. This approach also has close ties to what's known as "Information Geometry" --- which quantifies this statistical information in an elegant way. Our [first application of these methods]({{< ref "/publication/brehmer-2019-gmn/index.md" >}}) was to the associated W-Higgs production mode, where we used our information geometry approach to evaluate the utility of the so-called "Simplified Template Cross Sections". In the future we hope to extend this approach to other gauge/Higgs processes, and gain more insight into the connections between Information Geometry, Machine Learning, and their applications to studying the SMEFT.

An orthogonal direction is to understand the effects of higher-order QCD corrections in the case of the SMEFT. While there has been tremendous progress in making predictions for Standard Model processes with greater and greater accuracy, usually, only the lowest-order calculations are used for beyond the Standard Model predictions. While this is sometimes fine as a first approximation, there are some cases where computing higher order corrections in the presence of SMEFT effects is important as well. In a [recent paper]({{< ref "/publication/baglio-2019-uty/index.md" >}}) we demonstrated that higher-order effects are extremely important in WZ production, and dramatically change the limits obtained from LHC data. In the future, we'll continue to extend this approach to other processes, and try to understand the consequences in a global fit to gauge/Higgs data.
