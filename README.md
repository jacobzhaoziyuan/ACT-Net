

<div align="center">

# ACT-Net: Asymmetric Co-Teacher Network for Semi-supervised Memory-efficient Medical Image Segmentation

[![MICCAI2022](https://img.shields.io/badge/arXiv-2207.01900-blue)](https://arxiv.org/abs/2207.01900)
[![MICCAI2022](https://img.shields.io/badge/Conference-ICIP2022-green)](https://ieeexplore.ieee.org/document/9919170)



</div>

Pytorch implementation of our method for IEEE ICIP 2022 paper: "ACT-Net: Asymmetric Co-Teacher Network for Semi-supervised Memory-efficient Medical Image Segmentation
". (Our code will be release soon.)

## Abstract
The success of deep convolutional neural networks (DCNNs) benefits from high volumes of annotated data. However, annotating medical images is laborious, expensive, and requires human expertise, which induces the label scarcity problem. Especially when encountering the domain shift, the problem becomes more serious. Although deep unsupervised domain adaptation (UDA) can leverage well-established source domain annotations and abundant target domain data to facilitate cross-modality image segmentation and also mitigate the label paucity problem on the target domain, the conventional UDA methods suffer from severe performance degradation when source domain annotations are scarce. In this paper, we explore a challenging UDA setting - limited source domain annotations. We aim to investigate how to efficiently leverage unlabeled data from the source and target domains with limited source annotations for cross-modality image segmentation. To achieve this, we propose a new label-efficient UDA framework, termed MT-UDA, in which the student model trained with limited source labels learns from unlabeled data of both domains by two teacher models respectively in a semi-supervised manner. More specifically, the student model not only distills the intra-domain semantic knowledge by encouraging prediction consistency but also exploits the inter-domain anatomical information by enforcing structural consistency. Consequently, the student model can effectively integrate the underlying knowledge beneath available data resources to mitigate the impact of source label scarcity and yield improved cross-modality segmentation performance. We evaluate our method on MM-WHS 2017 dataset and demonstrate that our approach outperforms the state-of-the-art methods by a large margin under the source-label scarcity scenario.

<p align="center">
<img src="https://github.com/jacobzhaoziyuan/ACT-Net/blob/main/assets/archi_act.png" width="800">
</p>







## Citation
If you find the codebase useful for your research, please cite the paper:
```
@misc{zhao2022actnet,
    title={ACT-Net: Asymmetric Co-Teacher Network for Semi-supervised Memory-efficient Medical Image Segmentation},
    author={Ziyuan Zhao and Andong Zhu and Zeng Zeng and Bharadwaj Veeravalli and Cuntai Guan},
    year={2022},
    eprint={2207.01900},
    archivePrefix={arXiv},
    primaryClass={eess.IV}
}

```
