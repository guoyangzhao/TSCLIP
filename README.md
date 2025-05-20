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
We constructed the CRTS dataset with over 190,000 images, integrating traffic sign from 10 regions. The CRTS standardizes 46 commonly used categories with unified labels for consistent cross-regional recognition.
The download link for the CRTS dataset is **[HERE](https://drive.google.com/drive/folders/1YKZe9YnWN-sNmsD1EIT5J5dimxPqSwyV?usp=sharing)**.

<img src="https://github.com/guoyangzhao/TSCLIP/blob/main/images/sign_distribution.png" width="80%" height="auto">


### Citations:
If you find TSCLIP useful in your research or applications, please consider giving us a star 🌟 and citing it.

```bibtex
@misc{zhao2024tscliprobustclipfinetuning,
      title={TSCLIP: Robust CLIP Fine-Tuning for Worldwide Cross-Regional Traffic Sign Recognition}, 
      author={Guoyang Zhao and Fulong Ma and Weiqing Qi and Chenguang Zhang and Yuxuan Liu and Ming Liu and Jun Ma},
      year={2024},
      eprint={2409.15077},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2409.15077}, 
}
```
