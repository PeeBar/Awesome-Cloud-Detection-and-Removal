# Awesome-Cloud-Detection-and-Removal
Collection of popular and reproducible works of cloud detection and removal.


# Cloud Detection

## Benchmark dataset
* [38-Cloud](https://github.com/SorourMo/38-Cloud-A-Cloud-Segmentation-Dataset)
* [95-Cloud](https://github.com/SorourMo/95-Cloud-An-Extension-to-38-Cloud-Dataset)
* [HRC-WHU](https://github.com/dr-lizhiwei/HRC_WHU)

## Related Papers
|Pub|Year|Title|Code|
|:---:|:---:|:---:|:---:|
|ICCV|2019|[Generative Adversarial Training for Weakly Supervised Cloud Matting](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zou_Generative_Adversarial_Training_for_Weakly_Supervised_Cloud_Matting_ICCV_2019_paper.pdf)|[Code](https://github.com/flyakon/Pytorch-CloudMattingGAN)|
|IGARSS|2019|[Cloud-Net: An End-To-End Cloud Detection Algorithm for Landsat 8 Imagery](https://ieeexplore.ieee.org/document/8898776)|[Code](https://github.com/SorourMo/Cloud-Net-A-semantic-segmentation-CNN-for-cloud-detection)|
|RSE|2019|[A cloud detection algorithm for satellite imagery based on deep learning](https://www.sciencedirect.com/science/article/pii/S0034425719301294)|[Code](https://github.com/JacobJeppesen/RS-Net)|
|IEEE TGRS|2019|[CDnet: CNN-Based Cloud Detection for Remote Sensing Imagery](https://ieeexplore.ieee.org/document/8681238)|[Code](https://github.com/nkszjx/CDnetV2-pytorch-master)|
|IEEE JSTARS|2021|[Cloud and Cloud Shadow Segmentation for Remote Sensing Imagery Via Filtered Jaccard Loss Function and Parametric Augmentation](https://ieeexplore.ieee.org/document/9394710)|[-](https://github.com/SorourMo/95-Cloud-An-Extension-to-38-Cloud-Dataset)|
|RSE|2021|[Deep network based on up and down blocks using wavelet transform and successive multi-scale spatial attention for cloud detection](https://www.sciencedirect.com/science/article/pii/S0034425721002017)|-|
|IEEE TGRS|2022|[Dual-Branch Network for Cloud and Cloud Shadow Segmentation](https://ieeexplore.ieee.org/document/9775689)|-|

# Cloud Removal

## Benchmark dataset
* [RICE](https://github.com/BUPTLdy/RICE_DATASET), Arxiv
* GaoFen-1
* [Landsat8](https://earthexplorer.usgs.gov/), [Download Toturial](https://zhuanlan.zhihu.com/p/457230765)
* [Sentinel-2](https://sentinels.copernicus.eu/web/sentinel/missions/sentinel-2), [Download Toturial](https://www.bilibili.com/read/cv15264657/)

## Related Papers
|Pub|Year|Title|Code|
|:---:|:---:|:---:|:---:|
|CVPR|2016|[Removing Clouds and Recovering Ground Observations in Satellite Image Sequences via Temporally Contiguous Robust Matrix Completion](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Wang_Removing_Clouds_and_CVPR_2016_paper.html)|[Unofficial](https://github.com/AlexandreSev/Patch-Match)|
|IEEE TGRS|2016|[Cloud Removal Based on Sparse Representation via Multitemporal Dictionary Learning](https://ieeexplore.ieee.org/abstract/document/7383295)|[Unofficial](https://github.com/NicolasBizzozzero/Inpainting)|
|CVPRW|2017|[Filmy Cloud Removal on Satellite Imagery With Multispectral Conditional Generative Adversarial Nets](https://openaccess.thecvf.com/content_cvpr_2017_workshops/w18/html/Enomoto_Filmy_Cloud_Removal_CVPR_2017_paper.html)|[Code](https://github.com/enomotokenji/mcgan-cvprw2017-pytorch)|
|IGARSS|2018|[Cloud-Gan: Cloud Removal for Sentinel-2 Imagery Using a Cyclic Consistent Generative Adversarial Networks](https://ieeexplore.ieee.org/abstract/document/8519033)|-|
|Arxiv|2020|[Cloud Removal for Remote Sensing Imagery via Spatial Attention Generative Adversarial Network](https://arxiv.org/abs/2009.13015)|[Code](https://github.com/Penn000/SpA-GAN_for_cloud_removal)|
|WACV|2020|[Cloud Removal in Satellite Images Using Spatiotemporal Generative Models](https://arxiv.org/abs/1912.06838)|[Code](https://github.com/ermongroup/STGAN)|
|IEEE GRSL|2020|[Cloud-Aware Generative Network: Removing Cloud From Optical Remote Sensing Images](https://ieeexplore.ieee.org/document/8884095)|-|
|IEEE TGRS|2020|[Single Image Cloud Removal Using U-Net and Generative Adversarial Networks](https://ieeexplore.ieee.org/document/9224941)|[Unofficial](https://github.com/Yonv1943/CloudRemoval)|
|RSE|2020|[Accurate cloud detection in high-resolution remote sensing imagery by weakly supervised deep learning](https://www.sciencedirect.com/science/article/abs/pii/S0034425720304156?via%3Dihub)|[Project](https://skyearth.org/publication/project/WDCD/)|
|ISPRS|2020|[Cloud removal in Sentinel-2 imagery using a deep residual neural network and SAR-optical data fusion](https://www.sciencedirect.com/science/article/pii/S0924271620301398?via%3Dihub)|[Code](https://github.com/ameraner/dsen2-cr)|
|ISPRS|2020|[Thick cloud and cloud shadow removal in multitemporal images using progressively spatio-temporal patch group deep learning](https://www.sciencedirect.com/science/article/abs/pii/S0924271620300423)|[Code](https://github.com/qzhang95/PSTCR)|
|IGARSS|2021|[A Blind Cloud/Shadow Removal Strategy for Multi-Temporal Remote Sensing Images](https://ieeexplore.ieee.org/abstract/document/9554515)|-|
|IEEE TGRS|2022|[Thick Cloud Removal in Optical Remote Sensing Images Using a Texture Complexity Guided Self-Paced Learning Method](https://ieeexplore.ieee.org/abstract/document/9730910)|-|
|IEEE TGRS|2022|[A Unified Framework of Cloud Detection and Removal Based on Low-Rank and Group Sparse Regularizations for Multitemporal Multispectral Images](https://ieeexplore.ieee.org/document/9716079)|-|
|IEEE GRSL|2022|[Cloud Removal in Optical Remote Sensing Imagery Using Multiscale Distortion-Aware Networks](https://ieeexplore.ieee.org/document/9686746)|-|
|IEEE GRSL|2022|[Cloud Removal Using Multimodal GAN With Adversarial Consistency Loss](https://ieeexplore.ieee.org/document/9481173)|-|
|RS|2022|[Deep Internal Learning for Inpainting of Cloud-Affected Regions in Satellite Imagery](https://www.mdpi.com/2072-4292/14/6/1342)|[Code](https://github.com/cidcom/satellite-cloud-removal-dip)|
|RSE|2022|[Attention Mechanism-Based Generative Adversarial Networks for Cloud Removal in Landsat Images](https://www.sciencedirect.com/science/article/abs/pii/S0034425722000165)|[Code](http://jiasen.tech/documents/21/AMGAN-CR.rar)|
