# Thesis rebuttal - Supporting information
This repo contains supporting information for the Master Thesis rebuttal.

## 1) Comparison of proposed method against existing ones


| Backbone   | Method                  | BEN 10% LP | DFC2020 LP | DFC2020 FT | MADOS FT |
|------------|-------------------------|------------|------------|------------|----------|
| ViT-S      | MAE [1, 2]                    | 77.5       | 35.63      |       -     |    -      |
| ViT-S      | DINO [3, 2]                   | 81.7       | 32.34      |      -      |    -      |
| ViT-B      | I-JEPA [4, 5]                 |   -         | 36.72      |     -       |     -     |
| ViT-B      | SatMAE [6, 5]                  |   -         | 45.53      |     -       |      -    |
| ViT-L      | SatMAE [6, 5]                |   -         | 44.13      |     -       |      -    |
| ViT-B      | CROMA  [5]              | **85.04**  | 46.67      |       -     |     -     |
| ViT-L      | CROMA  [5]                | 85.01      | 49.78  |     -       |       -   |
| ResNet50   | SeCo  [7, 5]                  |     -       |     -       | 49.68      |   -       |
| ResNet50   | Sen12MS [8, 5]               |     -       |    -        | 54.83      |    -      |
| ResNet50   | SSL4EO-S12 [5]             |     -       |    -        | 54.68      |     -     |
| -         | MarineNeXt   [9]          |       -     |     -       |      -      | 64.3     |
| ViT-S      | Leo New Queue + DINO loss | 82.2 | **50.31**  | **57.91**  | **76.8** |

### References

[1] Kaiming He, Xinlei Chen, Saining Xie, Yanghao Li, Piotr Doll ´ar, and Ross Girshick.
Masked autoencoders are scalable vision learners, 2021.

[2] Yi Wang, Nassim Ait Ali Braham, Zhitong Xiong, Chenying Liu, Conrad M Albrecht,
and Xiao Xiang Zhu. Ssl4eo-s12: A large-scale multi-modal, multi-temporal dataset for
self-supervised learning in earth observation, 2023.

[3] Mathilde Caron, Hugo Touvron, Ishan Misra, Herve Jegou, Julien Mairal, Piotr Bo-
janowski, and Armand Joulin. Emerging properties in self-supervised vision transform-
ers, 2021.

[4] Mahmoud Assran, Quentin Duval, Ishan Misra, Piotr Bojanowski, Pascal Vincent, Michael Rabbat, Yann LeCun, and Nicolas Ballas. Self-supervised learning from images with a joint-embedding predictive architecture, 2023. 

[5] Anthony Fuller, Koreen Millard, and James R. Green. Croma: Remote sensing repre-
sentations with contrastive radar-optical masked autoencoders, 2023.

[6] Yezhen Cong, Samar Khanna, Chenlin Meng, Patrick Liu, Erik Rozi, Yutong He, Marshall
Burke, David B. Lobell, and Stefano Ermon. Satmae: Pre-training transformers for
temporal and multi-spectral satellite imagery, 2023.

[7] Oscar Manas, Alexandre Lacoste, Xavier Giro i Nieto, David Vazquez, and Pau Ro-
driguez. Seasonal contrast: Unsupervised pre-training from uncurated remote sensing
data, 2021.

[8] Michael Schmitt, Lloyd Haydn Hughes, Chunping Qiu, and Xiao Xiang Zhu. Sen12ms
– a curated dataset of georeferenced multi-spectral sentinel-1/2 imagery for deep
learning and data fusion, 2019.

[9] Katerina Kikaki, Ioannis Kakogeorgiou, Ibrahim Hoteit, and Konstantinos Karantzalos.
Detecting marine pollutants and sea surface features with deep learning in sentinel-2
imagery. ISPRS Journal of Photogrammetry and Remote Sensing, 210:39–54, 2024.

