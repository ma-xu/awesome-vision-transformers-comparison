# awesome-vision-transformers-comparison
A detailed comparsion of Recent Vision Transformers on ImageNet1k

| Model | Trait | ImgSize | Parms(M) | MACs(G) | Top1 | Code | Publish |
|--------------------------|-------|---------|--------------|-------------|-------------|---------------------------------------|----------------|
| New-ResNet18 |Conv | 224 | 12 | 1.8 | 70.6 | [timm](https://github.com/rwightman/pytorch-image-models) | [2021 Oct arXiv](https://arxiv.org/abs/2110.00476) |
| New-ResNet34 |Conv | 224 | 22 | 3.7 | 75.5 | [timm](https://github.com/rwightman/pytorch-image-models) | [2021 Oct arXiv](https://arxiv.org/abs/2110.00476) |
| New-ResNet50 | Conv| 224 | 26 | 4.1 | 79.8 | [timm](https://github.com/rwightman/pytorch-image-models) | [2021 Oct arXiv](https://arxiv.org/abs/2110.00476) |
| New-ResNet101 |Conv | 224 | 45 | 7.9 | 81.3 | [timm](https://github.com/rwightman/pytorch-image-models) | [2021 Oct arXiv](https://arxiv.org/abs/2110.00476) |
| New-ResNet152 | Conv| 224 | 60 | 11.6 | 81.8 | [timm](https://github.com/rwightman/pytorch-image-models) | [2021 Oct arXiv](https://arxiv.org/abs/2110.00476) |
| ViT-B/16 | SA| 224 | 86 | 17.6 | 79.7 | [timm](https://github.com/rwightman/pytorch-image-models) | [2021 ICLR](https://openreview.net/pdf?id=YicbFdNTTy)|
| ViT-L/16 |SA | 224 | 304.3 | 63.6 | 81.1 | [timm](https://github.com/rwightman/pytorch-image-models) | [2021 ICLR](https://openreview.net/pdf?id=YicbFdNTTy)|
| DeiT-S |SA | 224 | 22 | 4.6 | 79.8 | [timm](https://github.com/rwightman/pytorch-image-models) | [2021 ICML](https://arxiv.org/abs/2012.12877)|
| DeiT-B | SA| 224 | 86 | 17.5 | 81.8 | [timm](https://github.com/rwightman/pytorch-image-models) | [2021 ICML](https://arxiv.org/abs/2012.12877)|
| PVT-Tiny |SA | 224 | 13 | 1.9 | 75.1 | [code](https://github.com/whai362/PVT)| [2021 ICCV](https://arxiv.org/pdf/2102.12122.pdf) |
| PVT-Small | SA| 224 | 25 | 3.8 | 79.8 | [code](https://github.com/whai362/PVT)|[2021 ICCV](https://arxiv.org/pdf/2102.12122.pdf) |
| PVT-Medium |SA | 224 | 44 | 6.7 | 81.2 |[code](https://github.com/whai362/PVT) |[2021 ICCV](https://arxiv.org/pdf/2102.12122.pdf) |
| PVT-Large | SA | 224 | 61 | 9.8 | 81.7 |[code](https://github.com/whai362/PVT) |[2021 ICCV](https://arxiv.org/pdf/2102.12122.pdf)|
| PVTv2-B1 | SA | 224 | 13.1  | 2.1  | 78.7 |[code](https://github.com/whai362/PVT) |[2022 CVM](https://link.springer.com/article/10.1007/s41095-022-0274-8)|
| PVTv2-B2 | SA | 224 | 25.4 | 4.0  | 82.0 |[code](https://github.com/whai362/PVT) |[2022 CVM](https://link.springer.com/article/10.1007/s41095-022-0274-8)|
| PVTv2-B3 | SA | 224 | 45.2 | 6.9 | 83.2 | [code](https://github.com/whai362/PVT) |[2022 CVM](https://link.springer.com/article/10.1007/s41095-022-0274-8)|
| PVTv2-B4 | SA | 224 | 62.6 | 10.1 | 83.6 |[code](https://github.com/whai362/PVT) |[2022 CVM](https://link.springer.com/article/10.1007/s41095-022-0274-8)|
| PVTv2-B5 | SA | 224 | 82.0 | 11.8 | 83.8 |[code](https://github.com/whai362/PVT) |[2022 CVM](https://link.springer.com/article/10.1007/s41095-022-0274-8)|
| MLP-Mixer-B/16 |MLP | 224 | 59 | 12.7 | 76.4 | [code](https://github.com/google-research/vision_transformer)| [2021 NIPS](https://arxiv.org/abs/2105.01601) |
| ResMLP-S12 | MLP| 224 | 15 | 3 | 76.6 |[timm](https://github.com/rwightman/pytorch-image-models) | [2021 May arXiv](https://arxiv.org/pdf/2105.03404.pdf) |
| ResMLP-S24 |MLP | 224 | 30 | 6 | 79.4 |[timm](https://github.com/rwightman/pytorch-image-models) |[2021 May arXiv](https://arxiv.org/pdf/2105.03404.pdf)  |
| ResMLP-B24 |MLP | 224 | 116 | 23 | 81 |[timm](https://github.com/rwightman/pytorch-image-models) |[2021 May arXiv](https://arxiv.org/pdf/2105.03404.pdf)  |
| Swin-Mixer-T/D24 |MLP | 256 | 20 | 4 | 79.4 |[code](https://github.com/microsoft/Swin-Transformer)  | [2021 ICCV](https://arxiv.org/pdf/2103.14030.pdf)|
| Swin-Mixer-T/D6 | MLP| 256 | 23 | 4 | 79.7 |[code](https://github.com/microsoft/Swin-Transformer)  | [2021 ICCV](https://arxiv.org/pdf/2103.14030.pdf)|
| Swin-Mixer-B/D24 |MLP | 224 | 61 | 10.4 | 81.3 |[code](https://github.com/microsoft/Swin-Transformer)  |[2021 ICCV](https://arxiv.org/pdf/2103.14030.pdf) |
| gMLP-S | MLP | 224 | 20 | 4.5 | 79.6 | [timm](https://github.com/rwightman/pytorch-image-models) | [2021 NIPS](https://proceedings.neurips.cc/paper/2021/file/4cc05b35c2f937c5bd9e7d41d3686fff-Paper.pdf) |
| gMLP-B | MLP | 224 | 73 | 15.8 |81.6 | [timm](https://github.com/rwightman/pytorch-image-models)| [2021 NIPS](https://proceedings.neurips.cc/paper/2021/file/4cc05b35c2f937c5bd9e7d41d3686fff-Paper.pdf) |
| PoolFormer-S12 | Pool | 224 | 12 | 2 | 77.2 | [code](https://github.com/sail-sg/poolformer) | [2022 CVPR](https://arxiv.org/abs/2111.11418) |
| PoolFormer-S24 | Pool | 224 | 21 | 3.6 | 80.3 | [code](https://github.com/sail-sg/poolformer) | [2022 CVPR](https://arxiv.org/abs/2111.11418) |
| PoolFormer-S36 | Pool | 224 | 31 | 5.2 | 81.4 | [code](https://github.com/sail-sg/poolformer) | [2022 CVPR](https://arxiv.org/abs/2111.11418) |
| PoolFormer-M36 | Pool | 224 | 56 | 9.1 | 82.1 | [code](https://github.com/sail-sg/poolformer) | [2022 CVPR](https://arxiv.org/abs/2111.11418) |
| PoolFormer-M48 | Pool | 224 | 73 | 11.9 | 82.5 | [code](https://github.com/sail-sg/poolformer) | [2022 CVPR](https://arxiv.org/abs/2111.11418) |
| Swin-T |SA | 224 | 29 | 4.5 | 81.3|[code](https://github.com/microsoft/Swin-Transformer)  |[2021 ICCV](https://arxiv.org/pdf/2103.14030.pdf) |
| Swin-S|SA | 224 | 50|  8.7 | 83.0| [code](https://github.com/microsoft/Swin-Transformer) | [2021 ICCV](https://arxiv.org/pdf/2103.14030.pdf)|
| Swin-B|SA | 224 | 88|  15.4 | 83.5|[code](https://github.com/microsoft/Swin-Transformer)  |[2021 ICCV](https://arxiv.org/pdf/2103.14030.pdf) |
| Swin-B| SA| 384 | 88|  47.0 | 84.5| [code](https://github.com/microsoft/Swin-Transformer) |[2021 ICCV](https://arxiv.org/pdf/2103.14030.pdf) |
| ActiveMLP-xT|MLP | 224 | 15|  2.2 | 79.7| [code, x](https://github.com/microsoft/ActiveMLP) |[2022 Mar](https://arxiv.org/pdf/2203.06108.pdf) |
| ActiveMLP-T|MLP | 224 | 27|  4.0 |82.0 | [code, x](https://github.com/microsoft/ActiveMLP) |[2022 Mar](https://arxiv.org/pdf/2203.06108.pdf) |
| ActiveMLP-S|MLP | 224 |39 | 6.9  | 83.0| [code, x](https://github.com/microsoft/ActiveMLP) |[2022 Mar](https://arxiv.org/pdf/2203.06108.pdf) |
| ActiveMLP-B|MLP | 224 | 52|   10.1| 83.5| [code, x](https://github.com/microsoft/ActiveMLP) |[2022 Mar](https://arxiv.org/pdf/2203.06108.pdf) |
| ActiveMLP-L|MLP | 224 |76 |  12.3 |83.6 | [code, x](https://github.com/microsoft/ActiveMLP) |[2022 Mar](https://arxiv.org/pdf/2203.06108.pdf) |
| VAN-Tiny|DW-Conv | 224 |4.1 |  0.9 |75.4 | [code](https://github.com/Visual-Attention-Network) |[2022 Feb](https://arxiv.org/pdf/2202.09741.pdf) |
| VAN-Small|DW-Conv | 224 | 13.9| 2.5  |81.1 | [code](https://github.com/Visual-Attention-Network) |[2022 Feb](https://arxiv.org/pdf/2202.09741.pdf) |
| VAN-Base|DW-Conv | 224 |26.6 |  5.0 |82.8 | [code](https://github.com/Visual-Attention-Network) |[2022 Feb](https://arxiv.org/pdf/2202.09741.pdf) |
| VAN-Large|DW-Conv | 224 | 44.8| 9.0  |83.9 | [code](https://github.com/Visual-Attention-Network) |[2022 Feb](https://arxiv.org/pdf/2202.09741.pdf) |
| VAN-Huge|DW-Conv | 224 | 60.3| 12.2  | 84.2| [code](https://github.com/Visual-Attention-Network) |[2022 Feb](https://arxiv.org/pdf/2202.09741.pdf) |




[comment]: <> (| Model|Trait | ImgSize | Param| Macs  | Top1| [code] |[2022 Feb]|)
