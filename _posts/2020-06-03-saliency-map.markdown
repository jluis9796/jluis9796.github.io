---
layout: post
title:  "Learning from demonstration"
date:   2020-05-24 13:08:36 +0900
---
# Theory
* Saliency map calculation and applications <a href="https://www.jstage.jst.go.jp/article/jnns/21/1/21_3/_pdf/-char/ja">(日本語)</a>
* Saliency map calculation <a href="https://www.tu-chemnitz.de/informatik/KI/scripts/ws0910/Attention_Saliency.pdf">(English)</a>

# Computational model
https://github.com/akisatok/pySaliencyMap/blob/master/pySaliencyMap.py

* Color (RGB map) and Intensity (Gray map)
* Gaber Filter <a href="https://en.wikipedia.org/wiki/Gabor_filter">(Wikipedia)</a><a href="https://zenodo.org/record/3430156#.XtbrlzozbIU">Coding Facial Expressions with Gabor Wavelets</a>
* Pyramid (Gaussian Pyramid) <a href="https://en.wikipedia.org/wiki/Pyramid_(image_processing)"> Wikipedia</a>
* Taking center-surround differences of Gaussian Pyramid
* Feature maps
* Conspicuity maps
* Saliency map
* (Winner-take-all)
