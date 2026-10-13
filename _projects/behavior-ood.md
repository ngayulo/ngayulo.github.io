---
layout: project
order: 2

# ---- shown on the card AND the page ----
title: "Evaluating Object Recognition Behavioral Consistency on Out-of-Distribution Stimuli"
summary: "Evaluated the behavior consistency of Vision models with Humans on out-of-distribution stimuli."
meta: "Completed at MIT Summer Research Program (2021)"

# ---- the figure ----
# Replace with your own image in /images/projects/. Export at 1400px wide.
figure: /images/projects/behaviorOOD_methods.png
thumbnail:            # optional; falls back to `figure`
caption: "We trained a logistic regression model on vision models to predict out-of-distribution data and measure the behavior consistency of the output against the human choice."

# ---- materials: a button appears only if the field is filled ----
pdf:                  # e.g. /files/name.pdf
poster: /files/poster.pdf           # e.g. /files/name-poster.pdf
talk:                 # e.g. https://youtu.be/...
code:  https://github.com/ngayulo/behaviorConsistencyOOD/tree/main               # e.g. https://github.com/ngayulo/...
---

Towards understanding the human brain, neuroscientists have taken to reverse-engineering the brain using artificial neural networks (ANN). As vision models approach state of the art, neuroscientists are interested in evaluating their behavior consistency with human behavior. [Geirhos et al](https://proceedings.neurips.cc/paper_files/paper/2020/file/9f6992966d4c363ea0162a056cb45fe5-Paper.pdf) found ANN are at chance on predicting human choices given out-of-distribution (OOD) data (data not used for training the model). We examined this claim through its choice of readout and error consistency metric.

We trained a logistic regression model on various vision models to predict the class from a OOD image. We found that this decoder readout reflects higher behavior consistency than reported in Geirhos et al, which used the Wordnet decoder. While there is weak behaviorial consistency, it is not "at chance". 

<p align="center">
  <img src="/images/projects/behaviorOOD_results.png" alt="(top) ANNs generally underform human accuracy on classifying out-of-distribution images. (bottom) A decoder readout via a logistic regression model shows that behavior consistency is higher at reported." width="500" style="border: 1px solid gray"/>
</p>