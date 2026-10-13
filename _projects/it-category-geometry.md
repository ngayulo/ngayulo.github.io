---
layout: project
order: 1

# ---- shown on the card AND the page ----
title: "Geometry of Hierarchical Categories in Monkey IT"
summary: "Studied the geometry of neural manifolds in monkey IT cortex using theory of manifold capacity."
meta: "Cosyne 2024"

# ---- the figure ----
# Replace with your own image in /images/projects/. Export at 1400px wide.
figure: /images/projects/cosyne-figure.png
thumbnail: /images/projects/cosyne-figure-thumb.png          # optional; falls back to `figure`
caption: "(A) The human intuitive hierarchy organization for 13 manifolds. (B) Capacity, mean raw width, and mean center norm for manifolds at each level of abstraction, compared against manifolds with shuffled labels. Center norm describes a manifold’s distance from the global mean. Raw width summarizes the size of the manifold using points on its convex hull that is derived from capacity theory."

# ---- materials: a button appears only if the field is filled ----
pdf: /files/Category_Hierarchy__Cosyne_.pdf              # e.g. /files/it-category-geometry.pdf
poster:               # e.g. /files/it-category-geometry-poster.pdf
talk: https://youtu.be/ccG6ctQpUZY?t=4201
code:                 # e.g. https://github.com/ngayulo/...
---

Psychological have shown that humans tend to organize objects hierarchically based on abstraction of shared attributes. Neuroscience studies have found evidence for such hierarchical organization through similarity analyses of neural activities in the monkey IT ([Kiani et al, 2007](https://pubmed.ncbi.nlm.nih.gov/17428910/), [Kriegeskorte et al, 2008](https://www.frontiersin.org/journals/systems-neuroscience/articles/10.3389/neuro.06.004.2008/full)). In this project, we use the theory of manifold capacity ([Chung et al, 2018](https://journals.aps.org/prx/abstract/10.1103/PhysRevX.8.031003)) - a theoretical framework using statistical physics that connects object categorization to the geometry of the object's neural manifold ([^1]: A neural manifold is defined as the aggregated neural responses to each category.) - to discern the hierarchy structure of object classification in the monkey IT cortex. 

Applying manifold capacity theory shows that as the level of hierarchical classification increases (more general categories), distance to the manifold centers decreases while the size of the manifold seemingly remain constant. We hypothesize that the object manifolds are "stacked" and aligned along some axis of low variance. However, applying a whitening procedure and a rotational process, show evidence against this hypothesis as whitening and rotating stacked manifolds would both destroy the separability of the neural manifolds (as measured by capacity). We support this through simulation - generating vectors that are hierarchically correlated by adding vectors along a predetermined tree ([Saxe et al, 2019](https://www.pnas.org/doi/10.1073/pnas.1820226116)).

See the talk at Cosyne 2024 linked below.

<div class="video-embed">
    <iframe src="https://www.youtube-nocookie.com/embed/ccG6ctQpUZY?start=4201" title="Cosyne 2024 talk - Nga Yu Lo" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen loading="lazy"></iframe>
</div>