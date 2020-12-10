# AViD Dataset: Anonymized Videos from Diverse Countries

[AViD](https://arxiv.org/abs/2007.05515) is a large-scale video dataset published at NeurIPS 2020 ([AViD NeurIPS details](https://neurips.cc/virtual/2020/public/poster_c28e5b0c9841b5ef396f9f519bf6c217.html) for video, poster and presentation information). It has 467k videos and 887 action classes. Importantly, AViD has several key attributes:

### Static
The collected videos have a Creative-Commons License, allowing us to create and distribute a static dataset collected from various web sources (e.g., Flickr, Instagram, etc.). Unlike other YouTube-based datasets (e.g., Kinetics), the dataset is static and easily downloadable enabling reproducible research. We further release this dataset under a flexible MIT license, unlike more restrictive video datasets (e.g., Moments-in-Time and SomethingSomething). The dataset has similar size to the other standard video datasets.

<img src="https://github.com/piergiaj/AViD/raw/master/datasetsize.png" >


### Anonymized 
All the faces in the videos have been blurred so that no person can be identified.

<img src="https://github.com/piergiaj/AViD/raw/master/tractor.gif" alt="Driving Tractor" width=180> <img src="https://github.com/piergiaj/AViD/raw/master/ice_climb.gif"  alt="Ice Climb"> <img src="https://github.com/piergiaj/AViD/raw/master/shake_head.gif" alt="Shake Head" width=180> <img src="https://github.com/piergiaj/AViD/raw/master/arch_excv.gif" alt="Archaeological Excavation" width=180>

### Diverse
The videos have been collected from a wide range of countries and sources. This is important as some actions, for example greeting, are performed differently in different cultures. Other actions, like news broadcasts, can have different text depending on the country.  We find the model is unable to recognize videos from different countries without diverse training data (Tables 3, 4 and 5 in the paper).

<img src="https://github.com/piergiaj/AViD/raw/master/geographic.png" width="40%">


## Classes
The AViD dataset consists of 887 activity classes, capturing similiar actions to those in Kinetics, plus some additional actions such as talking, explosion, boating, etc. The classes follow a long-tailed distribution. More details on the classes and hierarchy of actions are described in the paper.

<img src="https://github.com/piergiaj/AViD/raw/master/longtail.png" width="25%">


# Baselines

|  Method | AViD Accuracy | 
| ------------- | ------------- |  
| 2D ResNet-50 | 36.2  | 
| I3D | 46.8 |
| 3D ResNet-50 | 48.2 |
| Two-Stream 3D ResNet-50 | 50.1 |
| RepFlow | 50.5 |
| (2+1)D ResNet-50 | 48.8 |
| SlowFast-50 4x4 | 48.5 |
| SlowFast-50 8x8 | 50.4 |
| SlowFast-101 16x8 | 50.9 |

# Dataset
The annotations are provided in this repository, in the [dataset](https://github.com/piergiaj/AViD/tree/master/dataset) directory. This contains the [full dataset](https://github.com/piergiaj/AViD/blob/master/dataset/avid_full.json) with labels and weak tags as well as classification-only [train](https://github.com/piergiaj/AViD/blob/master/dataset/avid_train.json) and [validation](https://github.com/piergiaj/AViD/blob/master/dataset/avid_val.json) sets.

The videos can be downloaded. Please fill out the [form](https://forms.gle/t5PSx2aUvQCRUZCi8) to get a link.


# Paper

AJ Piergiovanni and Michael S. Ryoo
"AViD Dataset: Anonymized Videos from Diverse Countries"
in NeurIPS 2020

[arXiv](https://arxiv.org/pdf/2007.05515.pdf)

    @inproceedings{aviddataset,
          title={AViD Dataset: Anonymized Videos from Diverse Countries},
          booktitle={Advances in Neural Information Processing Systems (NeurIPS)},
          author={AJ Piergiovanni and Michael S. Ryoo},
          year={2020}
    }
