# CNDataset_Gender-related

## Introduction

The re-annotated versions of two classic Chinese datasets (SWSR and TOXICN), with each dataset annotated by males and females respectively. They can be used to analyze the differences in annotations by different genders and their impact on models.

中文数据集的重新标注（SWSR与TOXICN），每个数据集由男性，女性分别标注，可用于分析不同性别标注的差异性，以及在使用预训练模型时对模型的影响。

---
## 原数据集：

### SWSR 数据集 - SWSR-Dataset

**Reference:**
Jiang A, Yang X, Liu Y, et al. SWSR: A Chinese dataset and lexicon for online sexism detection[J]. Online Social Networks and Media, 2022, 27: 100182.

**GitHub Download Link:** [SWSR Dataset](https://zenodo.org/records/4773875)

---

### TOXICN 数据集 - TOXICN-Dataset

**Reference:**
Lu J, Xu B, Zhang X, et al. Facilitating fine-grained detection of Chinese toxic language: Hierarchical taxonomy, resources, and benchmarks[J]. arxiv preprint arxiv:2305.04446, 2023.

**GitHub Download Link:** [TOXICN Dataset](https://github.com/DUT-lujunyu/ToxiCN)

---

### 文件介绍

**swsr-male：** 由男性标注者独立进行的，对SWSR数据集的毒性二分类重新标注；This subset of the SWSR dataset was re-annotated for binary toxicity classification by male annotators independently
**toxicn-male：** 由男性标注者独立进行的，对Toxicn数据集的毒性二分类重新标注；This subset of the Toxicn dataset was re-annotated for binary toxicity classification by male annotators independently
**swsr-female：** 由女性标注者独立进行的，对SWSR数据集的毒性二分类重新标注；This subset of the SWSR dataset was re-annotated for binary toxicity classification by female annotators independently
**toxicn-female：** 由女性标注者独立进行的，对Toxicn数据集的毒性二分类重新标注；This subset of the Toxicn dataset was re-annotated for binary toxicity classification by female annotators independently
**swsr-男女标注相异：** SWSR数据集标注完成后，将男性标注结果与女性标注结果进行比较，筛选出男女标注结果相异的部分；After the annotation of the SWSR dataset was completed, the annotations by male and female annotators were compared, and the parts with differing results were selected
**toxicn-男女标注相异：** Toxicn数据集标注完成后，将男性标注结果与女性标注结果进行比较，筛选出男女标注结果相异的部分；After the annotation of the Toxicn dataset was completed, the annotations by male and female annotators were compared, and the parts with differing results were selected

---

### Cite

**SWSR:**
A. Jiang, X. Yang, Y. Liu and A. Zubiaga (2021). SWSR: A Chinese Dataset and Lexicon for Online Sexism Detection. Under review

**TOXICN:**
```bibtex
@inproceedings{lu-etal-2023-facilitating,
    title = "Facilitating Fine-grained Detection of {C}hinese Toxic Language: Hierarchical Taxonomy, Resources, and Benchmarks",
    author = "Lu, Junyu  and
      Xu, Bo  and
      Zhang, Xiaokun  and
      Min, Changrong  and
      Yang, Liang  and
      Lin, Hongfei",
    booktitle = "Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = jul,
    year = "2023",
    address = "Toronto, Canada",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.acl-long.898",
    doi = "10.18653/v1/2023.acl-long.898",
    pages = "16235--16250",
}
