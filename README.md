# Vision-Mamba2
Vision Mamba 2: More Efficient Visual Representation Learning with State Space Duality
| Dataset | model | date | epoch | top1 | top5 | Checkpoint |
|-------|-------|-------|-------|-------|-------|-------|
| ImageNet 1k | DeiT-tiny(baseline) | - | 300 | 72.2 | 91.1 | |
| ImageNet 1k | [Vim-tiny](https://github.com/hustvl/Vim) (baseline) | - | 300 | 76.1 | 93.0 |  |
| ImageNet 1k | Vim2-tiny | - | 0(training) | - | - |  |
# News
## 2024.6.11
We fixed some bugs, the base code is based on Vim and Mamba2, we will update the latest experimental results later.
## 2024.6.4
We are running experiments on imagenet1k and will make the code and weights public later!
## Citation
If you find Vision mamba2 is useful in your research or applications, please consider giving us a star 🌟 and citing it by the following BibTeX entry.

```bibtex
 @article{vim2,
  title={Vision Mamba 2: More Efficient Visual Representation Learning with State Space Duality},
  author={Ziwen Chen},
  year={2024}
}
```
