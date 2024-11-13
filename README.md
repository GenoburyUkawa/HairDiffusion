# HairDiffusion (NeurIPS 2024)

### Vivid Multi-Colored Hair Editing via Latent Diffusion

[![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/abs/2410.21789)
[![GitHub Stars](https://img.shields.io/github/stars/GenoburyUkawa/HairDiffusion?style=social)](https://github.com/GenoburyUkawa/HairDiffusion)

## Overview

![](assets/fig03_4.jpg "")


> **Abstract**: <br>
> Hair editing is a critical image synthesis task that aims to edit hair color and hairstyle using text descriptions or reference images, while preserving irrelevant attributes (e.g., identity, background, cloth). Many existing methods are based on StyleGAN to address this task. However, due to the limited spatial distribution of StyleGAN, it struggles with multiple hair color editing and facial preservation. Considering the advancements in diffusion models, we utilize Latent Diffusion Models (LDMs) for hairstyle editing. Our approach introduces Multi-stage Hairstyle Blend (MHB), effectively separating control of hair color and hairstyle in diffusion latent space. Additionally, we train a warping module to align the hair color with the target region. To further enhance multi-color hairstyle editing, we fine-tuned a CLIP model using a multi-color hairstyle dataset. Our method not only tackles the complexity of multi-color hairstyles but also addresses the challenge of preserving original colors during diffusion editing. Extensive experiments showcase the superiority of our method in editing multi-color hairstyles while preserving facial attributes given textual descriptions and reference images.

![](assets/fig1(1026).jpg "Overview of our approach")

## Citation

If you make use of our work, please cite our paper:

```bibtex
@article{zeng2024hairdiffusion,
  title={HairDiffusion: Vivid Multi-Colored Hair Editing via Latent Diffusion},
  author={Zeng, Yu and Zhang, Yang and Liu, Jiachen and Shen, Linlin and Deng, Kaijun and He, Weizhao and Wang, Jinbao},
  journal={arXiv preprint arXiv:2410.21789},
  year={2024}
}
```