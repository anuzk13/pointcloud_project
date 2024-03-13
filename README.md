# 3D segmentation

Project exploring 3D segmentation of pointclouds.


## Models for semantic segmentation:

- [Open3D ML](https://github.com/isl-org/Open3D-ML/tree/main?tab=readme-ov-file#model-zoo): 
Clone the library and follow instructions for installation

# Models
- RandLA-Net ([github](https://github.com/QingyongHu/RandLA-Net)) RandLA-Net: Efficient Semantic Segmentation of Large-Scale Point Clouds.
Hu, Qingyong and Yang, Bo and Xie, Linhai and Rosa, Stefano and Guo, Yulan and Wang, Zhihua and Trigoni, Niki and Markham, Andrew
- Point Transformer ([github](https://github.com/Pointcept/Pointcept))
Hengshuang Zhao, Li Jiang, Jiaya Jia, Philip Torr, Vladlen Koltun
- Point Net ([github](https://github.com/charlesq34/pointnet)) PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation
Qi, Charles R and Su, Hao and Mo, Kaichun and Guibas, Leonidas J

# Requirements:
Open3D ML is not supported in windows

```
pip install requirements.txt
```

## Other software

### Colmap

Use colmap to create pointclouds from images https://colmap.github.io/

### Meshlab

Use meshlab to clean and align pointclouds https://www.meshlab.net/

## Gaussian Splats

Use luma-ai (https://lumalabs.ai/) or the original  Gaussian Splatting paper to create Gaussian Splats (https://github.com/graphdeco-inria/gaussian-splatting)

- [Clay Splat](https://lumalabs.ai/embed/4ae1a520-3c74-485f-85a2-c3138121914a?mode=sparkles&background=%23ffffff&color=%23000000&showTitle=true&loadBg=true&logoPosition=bottom-left&infoPosition=bottom-right&cinematicVideo=undefined&showMenu=false)

- [Living Room Splat](https://lumalabs.ai/embed/27aaa0e4-6042-448f-ae50-5db06eff379b?mode=sparkles&background=%23ffffff&color=%23000000&showTitle=true&loadBg=true&logoPosition=bottom-left&infoPosition=bottom-right&cinematicVideo=undefined&showMenu=false)