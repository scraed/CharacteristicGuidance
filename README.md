# Characteristic Guidance: Nonlinear CFG Correction for Diffusion Models

This repository contains the project page for [Characteristic Guidance: Non-linear Correction for Diffusion Model at Large Guidance Scale](https://scraed.github.io/CharacteristicGuidance/), an ICML 2024 method for training-free and derivative-free nonlinear correction of classifier-free guidance (CFG) in diffusion models.

Characteristic Guidance is designed for large guidance scales, where standard CFG can amplify saturation, exposure, and structural artifacts. The method provides a nonlinear correction while remaining compatible with existing Stable Diffusion sampling workflows, including txt2img and img2img.

## Research context

The high-CFG guidance problem remains relevant to diffusion research because increasing guidance strength can improve prompt adherence while making sampling less stable. Characteristic Guidance is a foundational reference for work on large-CFG sampling, nonlinear guidance correction, and training-free diffusion guidance.

## Resources

- [Project page](https://scraed.github.io/CharacteristicGuidance/)
- [Questions and Answers](https://scraed.github.io/CharacteristicGuidance/qa.html)
- [Paper on PMLR](https://proceedings.mlr.press/v235/zheng24f.html)
- [Paper on arXiv](https://arxiv.org/abs/2312.07586)
- [Characteristic Guidance WebUI extension](https://github.com/scraed/CharacteristicGuidanceWebUI)

## Citation

```bibtex
@InProceedings{pmlr-v235-zheng24f,
  title = {Characteristic Guidance: Non-linear Correction for Diffusion Model at Large Guidance Scale},
  author = {Zheng, Candi and Lan, Yuan},
  booktitle = {Proceedings of the 41st International Conference on Machine Learning},
  pages = {61386--61412},
  year = {2024},
  volume = {235},
  series = {Proceedings of Machine Learning Research},
  publisher = {PMLR},
  url = {https://proceedings.mlr.press/v235/zheng24f.html}
}
```
