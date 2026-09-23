# C2FXNet: Coarse-to-Fine Scene Expert for Unified Object Detection across Adverse Weather

<p align="center">
  <a href="https://arxiv.org/abs/2609.25693">
    <img src="https://img.shields.io/badge/arXiv-2609.25693-b31b1b.svg" alt="arXiv">
  </a>
  <a href="https://doi.org/10.1145/3767308.3834979">
    <img src="https://img.shields.io/badge/ACM_MM-2026-blue.svg" alt="ACM MM 2026">
  </a>
</p>

**Tianle Fang, Zhenbing Liu, Chong Yin, Bolun Li, Haoxiang Lu**

**Accepted by ACM Multimedia (ACM MM 2026)**

📄 **Paper:** [arXiv](https://arxiv.org/abs/2609.25693) | [PDF](https://arxiv.org/pdf/2609.25693) | [DOI](https://doi.org/10.1145/3767308.3834979)

## 📢 News

- **2026.09:** Our paper is now available on arXiv!
- **2026:** C2FXNet has been accepted by ACM Multimedia 2026.

## 📖 Abstract

Object detection in adverse weather remains challenging because severe
degradations weaken visual quality and disrupt semantic feature representations
across diverse scenes. Existing methods usually rely on condition-specific
designs, which limits their ability to generalize within a unified detector. In
this paper, we propose a Coarse-to-Fine Scene Expert Network (C2FXNet) that
achieves unified detection through hierarchical scene guidance. Specifically,
C2FXNet introduces a dual-level guidance mechanism consisting of a Multi-step
Reasoning Router (MRR), which performs GRU-based recurrent scene reasoning over
compressed multi-scale visual cues and frozen coarse scene prototypes, and a
Fine Scene Refinement (FSR) module, which uses image-specific semantic cues to
modulate high-level features for local variation handling. Furthermore, a
Scene-aware Mixture-of-Experts (SMoE) dynamically combines scene-specific
experts under the joint guidance of MRR and FSR. By coupling coarse scene
reasoning with fine-grained semantic refinement, C2FXNet enables robust
multi-scene detection without scene-specific training. Extensive experiments on
RTTS, ExDark, and our newly constructed Adverse Weather Dataset (AWD)
demonstrate that C2FXNet consistently outperforms state-of-the-art methods
across foggy, dark, and clear conditions, reaching 63.70%, 71.14%, and 54.19%
mAP on RTTS, ExDark, and AWD, respectively. The source code will be released at
https://github.com/PolarisFTL/C2FXNet.

## 🚀 Code

The source code will be released in this repository.

Stay tuned!

## 📝 Citation

If you find our work useful in your research, please consider citing our paper:

```bibtex
@misc{fang2026c2fxnet,
  title={C2FXNet: Coarse-to-Fine Scene Expert for Unified Object Detection across Adverse Weather},
  author={Tianle Fang and Zhenbing Liu and Chong Yin and Bolun Li and Haoxiang Lu},
  year={2026},
  eprint={2609.25693},
  archivePrefix={arXiv},
  primaryClass={cs.CV},
  url={https://arxiv.org/abs/2609.25693}
}
```

## 📬 Contact

For questions or suggestions, please feel free to open an issue in this repository.
