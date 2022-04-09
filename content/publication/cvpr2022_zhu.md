+++
abstract = "Shadow removal, which aims to restore the background in the shadow regions, is challenging due to the highly ill-posed nature. Most existing deep learning-based methods individually remove the shadow by only considering the content of the matched paired images, barely taking into account the auxiliary supervision of shadow generation on shadow removal procedure. In this work, we argue that shadow removal and generation are interrelated and could provide useful informative supervision for each other. Specifically, we propose a new Bijective Mapping Network (BMNet), which couples the learning procedures of shadow removal and shadow generation in a unified parameter-shared framework. With consistent two-way constraints and synchronous optimization of the two procedures, BMNet could effectively recover the underlying background contents during the forward shadow removal procedure. In addition, through statistic analysis on real-world datasets, we observe and verify that shadow appearances under different color spectrums are inconsistent. This motivates us to design a Shadow-Invariant Color Guidance Module (SICGM), which can explicitly utilize the learned shadow-invariant color information to guide network color restoration, thereby further reducing color-bias effects. Experiments on the representative ISTD, ISTD+ and SRD benchmarks show that our proposed network outperforms the state-of-the-art method \cite{fu2021auto} in de-shadowing performance, while only using its 0.25$\%$ network parameters and 6.25$\%$ floating point operations (FLOPs)."
date = "2022-03-04"
image = ""
image_preview = ""
math = false
publication = "CVPR 2022 (oral)"
publication_short = ""
selected = false
title = "Bijective Mapping Network for Shadow Removal"
url_code = ""
url_dataset = ""
url_pdf = ""
url_project = "/project/deeplearning"
url_slides = ""
url_video = ""

[[authors]]
    name = "Yurui Zhu"
    is_member = true
[[authors]]
    name = "Jie Huang"
    is_member = true
[[authors]]
    name = "Xueyang Fu"
    is_member = true
[[authors]]
    name = "Feng Zhao"
    is_member = true
[[authors]]
    name = "Qibin Sun"
    is_member = true
[[authors]]
    name = "Zheng-Jun Zha"
    is_member = true
+++


You can add information in $\LaTeX$ and *Markdown* here.
