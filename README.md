<h1 align="center">GEM-Occ</h1>
<h3 align="center">From Visual Geometry Evidence to Embodied Semantic Occupancy Memory</h3>

<p align="center">
  Hu&nbsp;Zhu<sup>1,5</sup> &nbsp; Bohan&nbsp;Li<sup>2,5</sup> &nbsp; Xianda&nbsp;Guo<sup>3</sup> &nbsp; Yanlun&nbsp;Peng<sup>4</sup> &nbsp; Hongsi&nbsp;Liu<sup>5</sup> &nbsp; Baorui&nbsp;Peng<sup>6</sup><br>
  Xiaofeng&nbsp;Wang<sup>7</sup> &nbsp; Mingqi&nbsp;Yuan<sup>8</sup> &nbsp; Xin&nbsp;Jin<sup>5</sup> &nbsp; Wenjun&nbsp;Zeng<sup>5</sup> &nbsp; Chang&nbsp;Wen&nbsp;Chen<sup>1</sup>
</p>

<p align="center">
  <sup>1</sup>The Hong Kong Polytechnic University &nbsp; <sup>2</sup>Shanghai Jiao Tong University<br>
  <sup>3</sup>Wuhan University &nbsp; <sup>4</sup>Great Wall Motor &nbsp; <sup>5</sup>Eastern Institute of Technology, Ningbo<br>
  <sup>6</sup>Georgia Institute of Technology &nbsp; <sup>7</sup>Tsinghua University &nbsp; <sup>8</sup>The University of Hong Kong
</p>

<p align="center">
  <a href="https://arxiv.org/abs/2607.05543">Paper</a> &nbsp;|&nbsp;
  <a href="https://zhuhu00.top/GEM-Occ/">Project Page</a> &nbsp;|&nbsp;
  <a href="https://github.com/zhuhu00/GEM-Occ">Code</a> &nbsp;|&nbsp;
  <a href="https://huggingface.co/datasets/zhuhu00/HI-Occ">Data</a>
</p>

## Overview

**GEM-Occ** is a Gaussian Evidence Memory framework for embodied semantic occupancy mapping. It converts local predictions into occupied semantic Gaussians and free-space ray evidence, then integrates them into persistent memory through confidence- and visibility-aware causal updates. Hierarchical memory organization supports continued mapping and efficient occupancy queries across connected indoor spaces.

**HIOcc** is a unified benchmark constructed from ScanNet, ScanNet++, and Matterport3D. It provides a shared semantic label space and evaluation framework for local prediction, room-level online mapping, and building-level mapping, with perspective and panoramic observations.

## Resources and availability

- **Paper and results:** see the [paper](https://arxiv.org/abs/2607.05543) and [project page](https://zhuhu00.top/GEM-Occ/) for the method, benchmark, and qualitative results.
- **Dataset:** HIOcc is available through [Hugging Face](https://huggingface.co/datasets/zhuhu00/HI-Occ). File access requires signing in and accepting the repository's access conditions; see its dataset card for the released files and usage instructions.
- **Code and checkpoints:** this repository currently hosts the project documentation. The implementation, trained checkpoints, and scripts for dataset construction, training, and evaluation are planned for release.

## Citation

```bibtex
@misc{zhu2026gemoccvisualgeometryevidence,
  title         = {From Visual Geometry Evidence to Embodied Semantic Occupancy Memory},
  author        = {Hu Zhu and Bohan Li and Xianda Guo and Yanlun Peng and Hongsi Liu and Baorui Peng and Xiaofeng Wang and Mingqi Yuan and Xin Jin and Wenjun Zeng and Chang Wen Chen},
  year          = {2026},
  eprint        = {2607.05543},
  archivePrefix = {arXiv},
  primaryClass  = {cs.RO},
  url           = {https://arxiv.org/abs/2607.05543}
}
```
