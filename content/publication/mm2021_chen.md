+++
abstract = "Deep learning-based dense object detectors have achieved great success in the past few years and have been applied to numerous multimedia applications such as video understanding. However, the current training pipeline for dense detectors is compromised to lots of conjunctions that may not hold. In this paper, we investigate three such important conjunctions: 1) only samples assigned as positive in classification head are used to train the regression head; 2) classification and regression share the same input feature and computational fields defined by the parallel head architecture; and 3) samples distributed in different feature pyramid layers are treated equally when computing the loss. We first carry out a series of pilot experiments to show disentangling such conjunctions can lead to persistent performance improvement. Then, based on these findings, we propose Disentangled Dense Object Detector (DDOD), in which simple and effective disentanglement mechanisms are designed and integrated into the current state-of-the-art dense object detectors. Extensive experiments on MS COCO benchmark show that our approach can lead to 2.0 mAP, 2.4 mAP and 2.2 mAP absolute improvements on RetinaNet, FCOS, and ATSS baselines with negligible extra overhead. Notably, our best model reaches 55.0 mAP on the COCO test-dev set and 93.5 AP on the hard subset of WIDER FACE, achieving new state-of-the-art performance on these two competitive benchmarks."
abstract_short = "Short version of abstract."
date = "2021-03-04"
image = ""
image_preview = ""
math = false
publication = "ACM Multimedia 2021"
publication_short = ""
selected = false
title = "Disentangle Your Dense Object Detector"
url_code = "//github.com/zehuichen123/DDOD"
url_dataset = ""
url_pdf = "https://arxiv.org/abs/2107.02963"
url_project = "/project/deeplearning"
url_slides = ""
url_video = ""

[[authors]]
    name = "Zehui Chen"
    is_member = true
[[authors]]
    name = "Chenhongyi Yang"
    is_member = true
[[authors]]
    name = "Qiaofei Li"
    is_member = true
[[authors]]
    name = "Feng Zhao"
    is_member = true
[[authors]]
    name = "Zheng-jun Zha"
    is_member = true
[[authors]]
    name = "Feng Wu"
    is_member = true
+++


You can add information in $\LaTeX$ and *Markdown* here.
