<div align="center">

<h1>ViewBridge: Revisiting Cross-View Localization from Image Matching</h1>

Panwang Xia<sup>1 *</sup>, 
Qiong Wu<sup>1 *</sup>, 
Lei Yu<sup>2</sup>, 
Yi Liu<sup>1</sup>, 
Mingtao Xiong<sup>1</sup>, 
Xudong Lu<sup>3</sup>,
Yi Liu<sup>1</sup>,
Haoyu Guo<sup>1</sup>,
Yongxiang Yao<sup>1</sup>,
Junjian Zhang<sup>2</sup>,
Xiangyuan Cai<sup>2</sup>,
Hongwei Hu<sup>2</sup>,
Zhi Zheng<sup>3</sup>,
Yongjun Zhang<sup>1</sup>, 
Yi Wan<sup>1 †</sup>.

<sup>1</sup> Wuhan University,  <sup>2</sup> Ant Group,  <sup>3</sup> The Chinese University of Hong Kong.

<sup>*</sup> Equally contribution
<sup>†</sup> Corresponding author

</div>

## 🔥 Update

**2025.08.14**
- The paper is post on arXiv!  [![Paper](http://img.shields.io/badge/paper-arXiv.2508.10716-B31B1B.svg)](https://arxiv.org/abs/2508.10716)

## ✅ To-Do
We welcome any questions or suggestions via the Issues section.
- [x] Initial repo structure.
- [ ] Codes and models.
- [ ] CVFM benchmark.

## 🌞 Abstract
Cross-view localization aims to estimate the 3-DoF pose of a ground-view image by aligning it with aerial or satellite imagery. Existing methods typically address this task through direct regression or feature alignment in a shared bird’s-eye view (BEV) space. Although effective for coarse alignment, these methods fail to establish fine-grained and geometrically reliable correspondences under large viewpoint variations, thereby limiting both the accuracy and interpretability of localization results. Consequently, we revisit cross-view localization from the perspective of image matching and propose a unified framework that enhances both matching and localization. Specifically, we introduce a Surface Model that constrains BEV feature projection to physically valid regions for geometric consistency, and a SimRefiner that adaptively refines similarity distributions to enhance match reliability. To further support research in this area, we present CVFM, the first benchmark with 32,509 cross-view image pairs annotated with pixel-level correspondences. Extensive experiments demonstrate that our approach achieves geometry-consistent and fine-grained correspondences across extreme viewpoints and further improves the accuracy and stability of cross-view localization. 



<figure>
<div align="center">
<img src=./figure/intro_fig.jpg width="100%">
</div>

<div align='center'>
 
**Figure 1. Cross-view localization and matching results.
Top: FG2. Bottom: Ours. Green arrows indicate ground-truth poses, and blue arrows indicate predicted poses. Green lines denote correct matches, while red lines denote incorrect ones. For clarity, corresponding objects across views are highlighted with consistent colors.**

</div>
<br>

<div align="center">
<img src=./figure/main_framework.jpg width="100%">
</div>

<div align='center'>

**Figure 2. Illustration of our framework.**

</div>

## 📖 CVFM Benchmark

Coming Soon.

## 🚀 Models

Coming Soon.

## 🔨 Usage

Coming Soon.

## 🍭 Results

### Quantitative results.

<figure>
<div align="center">
<img src=./figure/results_loc.png width="100%">
</div>

<br>

<figure>
<div align="center">
<img src=./figure/resutls_match.png width="100%">
</div>

<br>


### Qualitative results.
</div>
<br>

<figure>
<div align="center">
<img src=./figure/exp_vis.jpg width="100%">
</div>

<div align='center'>

**Figure 3. Visualization of cross-view localization on VIGOR. Corresponding objects are highlighted with consistent colors for visual clarity. Yellow lines indicate predicted matches. Since VIGOR does not provide pixel-level ground-truth correspondences, correctness cannot be assessed directly; instead, obvious mismatches are marked with red circles for qualitative comparison.**

</div>

<br>

</div>
<br>

<figure>
<div align="center">
<img src=./figure/match_vis.png width="100%">
</div>




## ⭐ Citation

If you find ViewBridge helpful, please give a ⭐ and cite it as follows:

```
@misc{xia2025viewbridge,
  title={ViewBridge: Revisiting Cross-View Localization from Image Matching},
  author={Xia, Panwang and Wu, Qiong and Yu, Lei and Liu, Yi and Xiong, Mingtao and Lu, Xudong and Guo, Haoyu and Yao, Yongxiang and Zhang, Junjian and Cai, Xiangyuan and others},
  journal={arXiv preprint arXiv:2508.10716},
  year={2025}
}
```

## 🎺 Statement

For any other questions please contact  Panwang Xia [xiapanwang@whu.edu.cn]  or  Qiong Wu [mabel_wq@whu.edu.cn].

