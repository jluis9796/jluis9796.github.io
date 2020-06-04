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
* Gabor Kernels & Gaussian Pyramid <a href="http://labs.eecs.tottori-u.ac.jp/sd/Member/oyamada/OpenCV/html/py_tutorials/py_imgproc/py_pyramids/py_pyramids.html"> (Example) </a>
* Taking center-surround differences of Gaussian Pyramid
* Feature maps
* Conspicuity maps
* Weigthing
* Bilateral Filter <a href="https://docs.opencv.org/3.0-last-rst/modules/imgproc/doc/filtering.html?highlight=laplacian#bilateralfilter">(link)</a>
* Binarize
* Grabcut <a href="https://qiita.com/marutaku0131/items/657c32358cfad7817648">(Link)</a>
* Saliency map
* (Winner-take-all)

**What is a steerable filter?** <a href="https://en.wikipedia.org/wiki/Steerable_filter"> (Wikipedia)</a>
* Gabor filter <a href="https://en.wikipedia.org/wiki/Gabor_filter">(Wikipedia)</a><a href="https://zenodo.org/record/3430156#.XtbrlzozbIU">(Coding Facial Expressions with Gabor Wavelets)</a>
* Steerable Pyramid <a href="https://www.cns.nyu.edu/~eero/STEERPYR/"> (Link) </a>
* Pyramid (Gaussian, Laplacian, Steerable) <a href="https://en.wikipedia.org/wiki/Pyramid_(image_processing)"> (Wikipedia)</a>

**Bilateral filtering** <a href="http://homepages.inf.ed.ac.uk/rbf/CVonline/LOCAL_COPIES/MANDUCHI1/Bilateral_Filtering.html">(Link)</a>
To prevent averaging across edges, while still averaging within smooth regions.

**Grab Cut**
マスクの設定値 cv2.GC_BGD:明らかに背景, cv2.GC_FGD:明らかに前景, cv2.GC_PR_BGD：背景かもしれない, cv2.GC_PR_FGD：前景かもしれない
