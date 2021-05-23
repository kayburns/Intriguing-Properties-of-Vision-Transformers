# Intriguing Properties of Vision Transformers

[Muzammal Naseer](https://scholar.google.ch/citations?user=tM9xKA8AAAAJ&hl=en),
[Kanchana Ranasinghe](https://scholar.google.com/citations?user=K2WBZTwAAAAJ),
[Salman Khan](https://scholar.google.com/citations?user=M59O9lkAAAAJ&hl=en),
[Munawar Hayat](https://scholar.google.ch/citations?user=Mx8MbWYAAAAJ&hl=en&oi=ao), 
[Fahad Shahbaz Khan](https://scholar.google.ch/citations?user=zvaeYnUAAAAJ&hl=en&oi=ao), &
[Ming-Hsuan Yang](https://scholar.google.com/citations?user=p9-ohHsAAAAJ&hl=en)

**[Paper Link](TBA)** 

> **Abstract:** 
>*Vision transformers (ViT) have demonstrated impressive performance across various machine vision tasks. These models are based on multi-head self-attention mechanisms that can flexibly attend to a sequence of image patches to encode contextual cues. An important question is how such flexibility (in attending image-wide4context conditioned on a given patch) can facilitate handling nuisances in natural images e.g., severe occlusions, domain shifts, spatial permutations, adversarial and natural perturbations. We systematically study this question via an extensive set of experiments encompassing three ViT families and provide comparisons with a high-performing convolutional neural network (CNN). We show and analyze the following intriguing properties of ViT: (a) Transformers are highly robust to severe occlusions, perturbations and domain shifts, e.g., retain as high as 60% top-1 accuracy on ImageNet even after randomly occluding 80% of the image content.  (b) The robust performance to occlusions is not due to a bias towards local textures, and ViTs are significantly less biased towards textures compared to CNNs. When properly trained to encode shape-based features, ViTs demonstrate shape recognition capability comparable to that of human visual system, previously unmatched in the literature. (c) Using ViTs to encode shape representation leads to an interesting consequence of accurate semantic segmentation without pixel-level supervision. (d) Off-the-shelf features from a single ViT model can be combined to create a feature ensemble, leading to high accuracy rates across a range of classification datasets in both traditional and few-shot learning paradigms.  We show effective features of ViTs are due to flexible and dynamic receptive fields possible via self-attention mechanisms. Our code will be publicly released.* 

## Citation

```bibtex
@misc{naseer2021intriguing,
      title={TBA}, 
      author={TBA},
      year={2021},
      eprint={TBA},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

## Table of Contents  
1) [Contributions](#Contributions) 
2) [Usage](#Usage)
3) [Pretrained Models](#Pretrained-Models) 
4) [Training](#Training)
5) [Evaluation](#Evaluation)
6) [Future Work?](#Future-Work)  

## Contributions

1. We explore how ViTs demonstrate strong robustness against severe occlusions for foreground objects, non-salient background and random patch locations, when compared with state-of-the-art CNNs. 
2. In relation to making decisions based off texture vs shape, we establish how ViTs are more shape biased than CNNs, and train them to reach shape recognition abilities comparable to humans. 
3. We highlight ViTs' better robustness to nuisance factors such as patch permutations, adversarial perturbations and common natural corruptions (e.g., noise, blur, contrast and pixelation artefacts) in comparison to CNNs.
4. We present a methodology for using off-the-shelf ViT features that generalize exceptionally well to new domains e.g., few-shot learning, fine-grained recognition, scene classification and long-tail recognition settings.

<p align="center">
  <img src="https://muzammal-naseer.github.io/intriguing-properties-of-vision-transformers/images/intro.png" width="50%" alt="explanation"/>
</p>


## Usage
TBA


## Pretrained Models
TBA


## Training
TBA

## Evaluation
TBA

## Future Work
TBA
