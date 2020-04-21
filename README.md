# AViD Dataset: Anonymized Videos from Diverse Countries

This is an early release of the dataset. The videos and labels are provided, more baseline results will be added shortly.

AViD is a large-scale video dataset with 467k videos and 887 action classes. Importantly, AViD has several key attributes:

### Static
The collected videos have a creative-commons license, allowing us to create and distribute a static dataset. Unlike other YouTube-based datasets (e.g., Kinetics), the dataset is static and easily downloadable enabling reproducible research. We further release this dataset under a flexible MIT license, unlike more restrictive video datasets (e.g., Moments-in-Time and SomethingSomething)

### Anonymized 
All the faces in the videos have been blurred so that no person can be identified.

### Diverse
The videos have been collected from a wide range of countries and sources. This is important as some actions, for example greeting, are performed differently in different cultures. Other actions, like news broadcasts, can have different text depending on the country. 

## Classes
The AViD dataset consists of 887 activity classes, capturing similiar actions to those in Kinetics, plus some additional actions such as talking, explosion, boating, etc. More details on the classes and hierarchy of actions will be described in the paper.


# Dataset
The annotations are provided in this repository, in the [dataset](https://github.com/piergiaj/AViD/tree/master/dataset) directory. This contains the [full dataset](https://github.com/piergiaj/AViD/blob/master/dataset/avid_full.json) with labels and weak tags as well as classification-only [train](https://github.com/piergiaj/AViD/blob/master/dataset/avid_train.json) and [validation](https://github.com/piergiaj/AViD/blob/master/dataset/avid_val.json) sets.

The videos can be downloaded. [AViD_small.tar.gz](https://drive.google.com/file/d/1lPfYCgm9t9YRBjllY_I02YLdFK7OEEGL/view?usp=sharing) (205 GB) contains all the videos resized so that the largest side is 256 pixels. [AViD_full.tar.gz](uploading) (330 GB) contains all the video are a max of 360p resolution.
