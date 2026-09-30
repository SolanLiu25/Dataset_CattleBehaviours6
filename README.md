# CattleBehaviours6

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23064957.svg)](https://doi.org/10.5281/zenodo.23064957)

**CattleBehaviours6** is a curated RGB video dataset for dairy cattle behaviour recognition. It contains **1,905 annotated video clips** across six indoor behaviours and is intended to support research in computer vision, multimodal learning, animal behaviour analysis, and precision livestock farming.

The dataset accompanies the paper **Cattle-CLIP: A Multimodal Framework for Dairy Cattle Behaviour Recognition from Video**.

## Paper

**Huimin Liu, Jing Gao, Daria Baran, Axel X Montout, Neill W. Campbell, Andrew W. Dowsey**

*Cattle-CLIP: A Multimodal Framework for Dairy Cattle Behaviour Recognition from Video.*

**AgriEngineering, 2026, 8(10), 410**

Paper: https://www.mdpi.com/2624-7402/8/10/410

## Dataset Download

The complete dataset is publicly available through Zenodo:

| Item | Link / value |
|---|---|
| Zenodo record | https://zenodo.org/records/23064957 |
| DOI | `10.5281/zenodo.23064957` |
| Version | `v1` |
| Archive | `CattleBehaviours6.zip` |
| Compressed size | 349.0 MB |
| Publication date | 30 September 2026 |

This GitHub repository provides a landing page for the dataset. The complete dataset files should be downloaded from the Zenodo archive.

## Dataset Overview

| Property | Description |
|---|---|
| Dataset | CattleBehaviours6 |
| Number of video clips | 1,905 |
| Number of behaviour classes | 6 |
| Modality | RGB video |
| Environment | Indoor dairy farm |
| Domain | Dairy cattle behaviour recognition |
| Primary task | Video behaviour classification |
| Repository | https://github.com/SolanLiu25/Dataset_CattleBehaviours6 |
| Data archive | https://zenodo.org/records/23064957 |

## Behaviour Classes

CattleBehaviours6 contains six behaviour categories:

| Label | Behaviour class |
|---:|---|
| 0 | Feeding |
| 1 | Drinking |
| 2 | Standing self-grooming |
| 3 | Standing ruminating |
| 4 | Lying self-grooming |
| 5 | Lying ruminating |

<p align="center">
  <img src="figures/cattle_behaviour_classes.png"
       alt="Overview of the six cattle behaviour classes in CattleBehaviours6"
       width="850">
</p>

<p align="center">
  <em>Overview of the six behaviour classes included in CattleBehaviours6.</em>
</p>

## Repository Contents

```text
.
|-- README.md
`-- figures/
    `-- cattle_behaviour_classes.png
```

The video files and dataset metadata are distributed through Zenodo rather than committed directly to this repository.

## Motivation

Automatic monitoring of cattle behaviour can provide useful information related to animal health, welfare, and productivity. Video-based cattle behaviour recognition is still challenging because publicly available annotated livestock video datasets are limited, cattle appearance and posture vary across camera views and lighting conditions, and agricultural surveillance footage differs substantially from general-purpose computer vision data.

CattleBehaviours6 was created as a curated benchmark for studying these challenges in indoor dairy farm environments.

## Cattle-CLIP

CattleBehaviours6 was introduced alongside **Cattle-CLIP**, a multimodal framework for dairy cattle behaviour recognition. Cattle-CLIP adapts Contrastive Language-Image Pretraining (CLIP) to video-based cattle behaviour understanding by incorporating temporal information and behaviour-specific semantic descriptions.

The associated paper evaluates Cattle-CLIP under both fully supervised and few-shot learning settings. Please refer to the paper for model details, experimental setup, and benchmark results.

## Citation

If you use CattleBehaviours6, please cite both the dataset and the associated paper.

```bibtex
@article{liu_2026_cattleclip,
  author  = {Liu, Huimin and Gao, Jing and Baran, Daria and Montout, Axel X. and Campbell, Neill W. and Dowsey, Andrew W.},
  title   = {Cattle-CLIP: A Multimodal Framework for Dairy Cattle Behaviour Recognition from Video},
  journal = {AgriEngineering},
  year    = {2026},
  volume  = {8},
  number  = {10},
  pages   = {410},
  url     = {https://www.mdpi.com/2624-7402/8/10/410}
}

@dataset{liu_2026_cattlebehaviours6,
  author    = {Liu, Huimin},
  title     = {CattleBehaviours6},
  year      = {2026},
  publisher = {Zenodo},
  version   = {v1},
  doi       = {10.5281/zenodo.23064957},
  url       = {https://doi.org/10.5281/zenodo.23064957}
}
```

## Contact

For questions or requests, please contact: sf24225@bristol.ac.uk.
