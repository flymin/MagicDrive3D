# MagicDrive3D

[![arXiv](https://img.shields.io/badge/ArXiv-2405.14475-b31b1b.svg?style=plastic)](https://arxiv.org/abs/2405.14475) [![web](https://img.shields.io/badge/Web-MagicDrive3D-blue.svg?style=plastic)](https://gaoruiyuan.com/magicdrive3d/) [![license](https://img.shields.io/github/license/flymin/MagicDrive3D?style=plastic)](https://github.com/flymin/MagicDrive3D/blob/main/LICENSE) [![star](https://img.shields.io/github/stars/flymin/MagicDrive3D)](https://github.com/flymin/MagicDrive3D)

This repository contains the implementation of the paper.

If you find our work useful, Please give us a star 🌟!

> MagicDrive3D: Controllable 3D Generation for Any-View Rendering in Street Scenes <br>
> [Ruiyuan Gao](https://gaoruiyuan.com/)<sup>1</sup>, [Kai Chen](https://kaichen1998.github.io/)<sup>2</sup>, [Zhihao Li](https://github.com/zhihaolee)<sup>3</sup>, [Lanqing Hong](https://scholar.google.com.sg/citations?user=2p7x6OUAAAAJ&hl=en)<sup>3^</sup>, [Zhenguo Li](https://scholar.google.com/citations?user=XboZC1AAAAAJ&hl=en)<sup>3</sup>, [Qiang Xu](https://cure-lab.github.io/)<sup>1^</sup><br>
> <sup>1</sup>CUHK <sup>2</sup>HKUST <sup>3</sup>Huawei Noah's Ark Lab <br>
> <sup>^</sup>Corresponding Authors

## Plan

We will release the code for scene reconstruction in this repo.

As for upgrades in video generation, we will merge the implementation to [MagicDrive-t](https://github.com/cure-lab/MagicDrive/tree/video) (i.e., video branch of [MagicDrive](https://github.com/cure-lab/MagicDrive)).

## Cite Us

```bibtex
@article{gao2024magicdrive3d,
  title={{MagicDrive3D}: Controllable 3D Generation for Any-View Rendering in Street Scenes},
  author={Gao, Ruiyuan and Chen, Kai and Li, Zhihao and Hong, Lanqing and Li, Zhenguo and Xu, Qiang},
  journal={arXiv preprint arXiv:2405.14475},
  year={2024}
}


@inproceedings{gao2023magicdrive,
  title={{MagicDrive}: Street View Generation with Diverse 3D Geometry Control},
  author={Gao, Ruiyuan and Chen, Kai and Xie, Enze and Hong, Lanqing and Li, Zhenguo and Yeung, Dit-Yan and Xu, Qiang},
  booktitle = {International Conference on Learning Representations},
  year={2024}
}
```

## Credit

We adopt the following open-sourced projects:

- [MagicDrive](https://github.com/cure-lab/MagicDrive): controllable street view video generation
- [gaussian-splatting](https://github.com/graphdeco-inria/gaussian-splatting): 3D reconstruction
- [ZoeDepth](https://github.com/isl-org/ZoeDepth): monocular metric depth estimation
