# PerfHD 
**PerfHD: Efficient ViT Architecture Performance Ranking using Hyperdimensional Computing**
- This repository provides a straightforward implementation of **PerfHD**, which leverage the capability of Hyperdimensional Computing (HDC) to tackle architecture performance ranking problem in ViT neural architecture search.

## Highlights
- **Straightforward.** **PerfHD** has straightforward implementation and the entire work can be summarized with one Jupyter notebook with less than 100 lines of Python code. 
- **Efficient, yet accurate.** Using just one GPU, **PerfHD** can rank nearly 100K ViT models in about just 1 minute. No pretraining or fine-tuning required. **PerfHD** is up to 100 times faster however still has competitive performance compared with SOTA algorithms. 

## Prerequisite Packages
- The following python packages are required to run the notebook:
```
json
torch
numpy
sklearn
scipy
tqdm
```
- Python >= 3.8
- GPU acceleration is strongly recommended however not strictly required. **PerfHD** is still fast using CPU only.

## Dataset
- The train and test data can be found [here](https://aistudio.baidu.com/aistudio/datasetdetail/134077) (CVPR 2022 NAS competition)

## Contact
- [Dongning Ma (Student)](mailto:dma2@villanova.edu), Xun Jiao (Professor), Villanova University
- Pengfei Zhao, Beijing Xiaochuan Technology Co., Ltd.

