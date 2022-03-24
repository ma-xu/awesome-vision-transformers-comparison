# awesome-vision-transformers-comparison
A detailed  comparsion of Recent Vision Transformers on ImageNet1k


\begin{table}[]
\begin{tabular}{llllllll}
Model & Trait & ImgSize & Parms(M) & MACs(G) & Top1 & Code & Publish \\
New-ResNet18 &  & 224 & 12 & 1.8 & 70.6 & timm & 2021 Oct arXiv \\
New-ResNet34 &  & 224 & 22 & 3.7 & 75.5 & timm & 2021 Oct arXiv \\
New-ResNet50 &  & 224 & 26 & 4.1 & 79.8 & timm & 2021 Oct arXiv \\
New-ResNet101 &  & 224 & 45 & 7.9 & 81.3 & timm & 2021 Oct arXiv \\
New-ResNet152 &  & 224 & 60 & 11.6 & 81.8 & timm & 2021 Oct arXiv \\
 &  & 224 &  &  &  &  &  \\
ViT-B/16 &  & 224 & 86 & 17.6 & 79.7 & timm &  \\
ViT-L/16 &  & 224 & 304.3 & 63.6 & 81.1 & timm &  \\
DeiT-S &  & 224 & 22 & 4.6 & 79.8 & timm &  \\
DeiT-B &  & 224 & 86 & 17.5 & 81.8 & timm &  \\
PVT-Tiny &  & 224 & 13 & 1.9 & 75.1 &  &  \\
PVT-Small &  & 224 & 25 & 3.8 & 79.8 &  &  \\
PVT-Medium &  & 224 & 44 & 6.7 & 81.2 &  &  \\
PVT-Large &  & 224 & 61 & 9.8 & 81.7 &  &  \\
MLP-Mixer-B/16 &  & 224 & 59 & 12.7 & 76.4 &  &  \\
ResMLP-S12 &  & 224 & 15 & 3 & 76.6 &  &  \\
ResMLP-S24 &  & 224 & 30 & 6 & 79.4 &  &  \\
ResMLP-B24 &  & 224 & 116 & 23 & 81 &  &  \\
Swin-Mixer-T/D24 &  & 256 & 20 & 4 & 79.4 &  &  \\
Swin-Mixer-T/D6 &  & 256 & 23 & 4 & 79.7 &  &  \\
Swin-Mixer-B/D24 &  & 224 & 61 & 10.4 & 81.3 &  &  \\
gMLP-S &  & 224 & 20 & 4.5 & 79.6 &  &  \\
gMLP-B &  & 224 & 73 & 15.8 &  &  &  \\
PoolFormer-S12 &  & 224 & 12 & 2 & 77.2 & https://github.com/sail-sg/poolformer & 2022 CVPR \\
PoolFormer-S24 &  & 224 & 21 & 3.6 & 80.3 & https://github.com/sail-sg/poolformer & 2022 CVPR \\
PoolFormer-S36 &  & 224 & 31 & 5.2 & 81.4 & https://github.com/sail-sg/poolformer & 2022 CVPR \\
PoolFormer-M36 &  & 224 & 56 & 9.1 & 82.1 & https://github.com/sail-sg/poolformer & 2022 CVPR \\
PoolFormer-M48 &  & 224 & 73 & 11.9 & 82.5 & https://github.com/sail-sg/poolformer & 2022 CVPR
\end{tabular}
\end{table}
