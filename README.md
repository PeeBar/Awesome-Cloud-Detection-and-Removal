# Awesome-Cloud-Detection-and-Removal
Collection of popular and reproducible works of cloud detection and removal.


# Cloud Detection

## Benchmark dataset
* [38-Cloud](https://github.com/SorourMo/38-Cloud-A-Cloud-Segmentation-Dataset)
* [95-Cloud](https://github.com/SorourMo/95-Cloud-An-Extension-to-38-Cloud-Dataset)
* [HRC-WHU](https://github.com/dr-lizhiwei/HRC_WHU)
* [SPARCS](https://www.usgs.gov/landsat-missions/spatial-procedures-automated-removal-cloud-and-shadow-sparcs-validation-data)
* [L8 Biome](https://landsat.usgs.gov/landsat-8-cloud-cover-assessment-validation-data)

## Related Papers
|Pub|Year|Title|Code|
|:---:|:---:|:---:|:---:|
|ICCV|2019|[Generative Adversarial Training for Weakly Supervised Cloud Matting](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zou_Generative_Adversarial_Training_for_Weakly_Supervised_Cloud_Matting_ICCV_2019_paper.pdf)|[Code](https://github.com/flyakon/Pytorch-CloudMattingGAN)|
|IGARSS|2019|[Cloud-Net: An End-To-End Cloud Detection Algorithm for Landsat 8 Imagery](https://ieeexplore.ieee.org/document/8898776)|[Code](https://github.com/SorourMo/Cloud-Net-A-semantic-segmentation-CNN-for-cloud-detection)|
|RSE|2019|[A cloud detection algorithm for satellite imagery based on deep learning](https://www.sciencedirect.com/science/article/pii/S0034425719301294)|[Code](https://github.com/JacobJeppesen/RS-Net)|
|RS|2019|[CloudFCN: Accurate and Robust Cloud Detection for Satellite Imagery with Deep Learning](https://www.mdpi.com/2072-4292/11/19/2312)|-|
|IEEE TGRS|2019|[CDnet: CNN-Based Cloud Detection for Remote Sensing Imagery](https://ieeexplore.ieee.org/document/8681238)|[Code](https://github.com/nkszjx/CDnetV2-pytorch-master)|
|RSE|2020|[Accurate cloud detection in high-resolution remote sensing imagery by weakly supervised deep learning](https://www.sciencedirect.com/science/article/abs/pii/S0034425720304156?via%3Dihub)|[Project](https://skyearth.org/publication/project/WDCD/)|
|IEEE TGRS|2021|[DABNet: Deformable Contextual and Boundary-Weighted Network for Cloud Detection in Remote Sensing Images](https://ieeexplore.ieee.org/abstract/document/9314019)|-|
|IEEE TGRS|2021|[Cloud Detection Method Using CNN Based on Cascaded Feature Attention and Channel Attention](https://ieeexplore.ieee.org/abstract/document/9576709)|-|
|IEEE JSTARS|2021|[Cloud and Cloud Shadow Segmentation for Remote Sensing Imagery Via Filtered Jaccard Loss Function and Parametric Augmentation](https://ieeexplore.ieee.org/document/9394710)|[-](https://github.com/SorourMo/95-Cloud-An-Extension-to-38-Cloud-Dataset)|
|RSE|2021|[Deep network based on up and down blocks using wavelet transform and successive multi-scale spatial attention for cloud detection](https://www.sciencedirect.com/science/article/pii/S0034425721002017)|-|
|IEEE TGRS|2022|[Dual-Branch Network for Cloud and Cloud Shadow Segmentation](https://ieeexplore.ieee.org/document/9775689)|-|

# Cloud Removal

## Benchmark dataset
* [RICE](https://github.com/BUPTLdy/RICE_DATASET)
* [GF1_WHU](https://github.com/dr-lizhiwei/GF1_WHU/tree/73cf7dd7727e9887b2e5695d6ef5d95cd1be00c3)
* [Landsat8](https://earthexplorer.usgs.gov/), [Download Toturial](https://zhuanlan.zhihu.com/p/457230765)
* [Sentinel-2](https://sentinels.copernicus.eu/web/sentinel/missions/sentinel-2), [Download Toturial](https://www.bilibili.com/read/cv15264657/)
* [WHUS2-CR](https://github.com/Neooolee/WHUS2-CR)
* [SEN12MS-CR](https://mediatum.ub.tum.de/1554803)
* [WHU Cloud Dataset](http://gpcv.whu.edu.cn/data/WHU_Cloud_Dataset.html)

## Related Papers
|Pub|Year|Title|Code|
|:---:|:---:|:---:|:---:|
|CVPR|2016|[Removing Clouds and Recovering Ground Observations in Satellite Image Sequences via Temporally Contiguous Robust Matrix Completion](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Wang_Removing_Clouds_and_CVPR_2016_paper.html)|[Unofficial](https://github.com/AlexandreSev/Patch-Match)|
|IEEE TGRS|2016|[Cloud Removal Based on Sparse Representation via Multitemporal Dictionary Learning](https://ieeexplore.ieee.org/abstract/document/7383295)|[Unofficial](https://github.com/NicolasBizzozzero/Inpainting)|
|CVPRW|2017|[Filmy Cloud Removal on Satellite Imagery With Multispectral Conditional Generative Adversarial Nets](https://openaccess.thecvf.com/content_cvpr_2017_workshops/w18/html/Enomoto_Filmy_Cloud_Removal_CVPR_2017_paper.html)|[Code](https://github.com/enomotokenji/mcgan-cvprw2017-pytorch)|
|IEEE GRSL|2018|[Haze and thin cloud removal via sphere model improved dark channel prior](https://ieeexplore.ieee.org/abstract/document/8500152)|-|
|IGARSS|2018|[Cloud-Gan: Cloud Removal for Sentinel-2 Imagery Using a Cyclic Consistent Generative Adversarial Networks](https://ieeexplore.ieee.org/abstract/document/8519033)|-|
|ISPRS|2018|[Cloud removal in remote sensing images using nonnegative matrix factorization and error correction](https://www.sciencedirect.com/science/article/abs/pii/S0924271618303484)|-|
|ISPRS|2019|[Blind cloud and cloud shadow removal of multitemporal images based on total variation regularized low-rank sparsity decomposition](https://www.sciencedirect.com/science/article/abs/pii/S092427161930214X)|[Code](https://chenyong1993.github.io/yongchen.github.io/papers/2019/TVLRSDC_code.zip)|
|Arxiv|2020|[Cloud Removal for Remote Sensing Imagery via Spatial Attention Generative Adversarial Network](https://arxiv.org/abs/2009.13015)|[Code](https://github.com/Penn000/SpA-GAN_for_cloud_removal)|
|RS|2020|[Cloud removal with fusion of high resolution optical and SAR images using generative adversarial networks](https://www.mdpi.com/2072-4292/12/1/191)|-|
|WACV|2020|[Cloud Removal in Satellite Images Using Spatiotemporal Generative Models](https://arxiv.org/abs/1912.06838)|[Code](https://github.com/ermongroup/STGAN)|
|IEEE GRSL|2020|[Cloud-Aware Generative Network: Removing Cloud From Optical Remote Sensing Images](https://ieeexplore.ieee.org/document/8884095)|-|
|IEEE TGRS|2020|[Single Image Cloud Removal Using U-Net and Generative Adversarial Networks](https://ieeexplore.ieee.org/document/9224941)|[Unofficial](https://github.com/Yonv1943/CloudRemoval)|
|IEEE TGRS|2020|[Simultaneous Cloud Detection and Removal From Bitemporal Remote Sensing Images Using Cascade Convolutional Neural Networks]()|-|
|ISPRS|2020|[Cloud removal in Sentinel-2 imagery using a deep residual neural network and SAR-optical data fusion](https://www.sciencedirect.com/science/article/pii/S0924271620301398?via%3Dihub)|[Code](https://github.com/ameraner/dsen2-cr)|
|ISPRS|2020|[Thick cloud and cloud shadow removal in multitemporal images using progressively spatio-temporal patch group deep learning](https://www.sciencedirect.com/science/article/abs/pii/S0924271620300423)|[Code](https://github.com/qzhang95/PSTCR)|
|IGARSS|2021|[A Blind Cloud/Shadow Removal Strategy for Multi-Temporal Remote Sensing Images](https://ieeexplore.ieee.org/abstract/document/9554515)|-|
|IEEE TGRS|2022|[Thick Cloud Removal in Optical Remote Sensing Images Using a Texture Complexity Guided Self-Paced Learning Method](https://ieeexplore.ieee.org/abstract/document/9730910)|-|
|IEEE TGRS|2022|[A Unified Framework of Cloud Detection and Removal Based on Low-Rank and Group Sparse Regularizations for Multitemporal Multispectral Images](https://ieeexplore.ieee.org/document/9716079)|-|
|IEEE GRSL|2022|[Cloud Removal in Optical Remote Sensing Imagery Using Multiscale Distortion-Aware Networks](https://ieeexplore.ieee.org/document/9686746)|-|
|IEEE GRSL|2022|[Cloud Removal Using Multimodal GAN With Adversarial Consistency Loss](https://ieeexplore.ieee.org/document/9481173)|-|
|RS|2022|[Deep Internal Learning for Inpainting of Cloud-Affected Regions in Satellite Imagery](https://www.mdpi.com/2072-4292/14/6/1342)|[Code](https://github.com/cidcom/satellite-cloud-removal-dip)|
|RS|2022|[Cloud Removal for Optical Remote Sensing Imagery Using Distortion Coding Network Combined with Compound Loss Functions](https://www.mdpi.com/2072-4292/14/14/3452)|-|
|RSE|2022|[Attention Mechanism-Based Generative Adversarial Networks for Cloud Removal in Landsat Images](https://www.sciencedirect.com/science/article/abs/pii/S0034425722000165)|[Code](http://jiasen.tech/documents/21/AMGAN-CR.rar)|
