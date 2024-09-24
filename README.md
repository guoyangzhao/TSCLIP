# TSCLIP
## TSCLIP: Robust CLIP Fine-tuning for Worldwide Cross-Regional Traffic Sign Recognition
[![arxiv paper](https://img.shields.io/badge/arXiv-Paper-red)](https://arxiv.org/abs/2409.15077)
<br>

### Motivation:
**Traffic sign cross-regional recognition and results.** (a) introduces the main content of this paper, fine-tuning TSCLIP on specific traffic sign datasets, and then performing recognition on other worldwide regions. (b) shows our TSCLIP model is far superior to the classic model and exceeds the mainstream CLIP fine-tuning scheme.

<img src="https://github.com/guoyangzhao/TSCLIP/blob/main/images/cross-region.png" width="40%" height="auto">

### Pattern differences of cross-regional traffic sign samples:
Four representative traffic signs (No Overtaking, No Parking, No Pedestrians, and Stop).

<img src="https://github.com/guoyangzhao/TSCLIP/blob/main/images/data-sample.png" width="70%" height="auto">

### Framework:
**Robust fine-tuning framework for TSCLIP model.** (a) shows the contrastive language-image training process of TSCLIP with traffic sign prompts (b) shows the Wise-FT scheme for weight ensembling of the CLIP model (c) shows our proposed Adaptive Dynamic Weight Ensembling (ADWE) scheme.

<img src="https://github.com/guoyangzhao/TSCLIP/blob/main/images/framework.png" width="60%" height="auto">


### Cross-Regional Traffic Sign (CRTS) Dataset:
We will make the dataset public as soon as possible. We have cleaned the data from 10 regions around the world.


### Citations:
If you find TSCLIP useful in your research or applications, please consider giving us a star 🌟 and citing it.
