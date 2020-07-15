# AViD Dataset: Anonymized Videos from Diverse Countries

This is an early release of the dataset. The videos and labels are provided, more baseline results will be added shortly.

AViD is a large-scale video dataset with 467k videos and 887 action classes. Importantly, AViD has several key attributes:

### Static
The collected videos have a creative-commons license, allowing us to create and distribute a static dataset. Unlike other YouTube-based datasets (e.g., Kinetics), the dataset is static and easily downloadable enabling reproducible research. We further release this dataset under a flexible MIT license, unlike more restrictive video datasets (e.g., Moments-in-Time and SomethingSomething)

### Anonymized 
All the faces in the videos have been blurred so that no person can be identified.

<img src="https://github.com/piergiaj/AViD/raw/master/tractor.gif" alt="Driving Tractor" width=180> <img src="https://github.com/piergiaj/AViD/raw/master/ice_climb.gif"  alt="Ice Climb"> <img src="https://github.com/piergiaj/AViD/raw/master/shake_head.gif" alt="Shake Head" width=180> <img src="https://github.com/piergiaj/AViD/raw/master/arch_excv.gif" alt="Archaeological Excavation" width=180>

### Diverse
The videos have been collected from a wide range of countries and sources. This is important as some actions, for example greeting, are performed differently in different cultures. Other actions, like news broadcasts, can have different text depending on the country. 

## Classes
The AViD dataset consists of 887 activity classes, capturing similiar actions to those in Kinetics, plus some additional actions such as talking, explosion, boating, etc. More details on the classes and hierarchy of actions will be described in the paper.


# Dataset
The annotations are provided in this repository, in the [dataset](https://github.com/piergiaj/AViD/tree/master/dataset) directory. This contains the [full dataset](https://github.com/piergiaj/AViD/blob/master/dataset/avid_full.json) with labels and weak tags as well as classification-only [train](https://github.com/piergiaj/AViD/blob/master/dataset/avid_train.json) and [validation](https://github.com/piergiaj/AViD/blob/master/dataset/avid_val.json) sets.

The videos can be downloaded. [AViD_small.tar.gz](https://drive.google.com/file/d/1lPfYCgm9t9YRBjllY_I02YLdFK7OEEGL/view?usp=sharing) (205 GB) contains all the videos resized so that the largest side is 256 pixels. [AViD_full.tar.gz](https://drive.google.com/file/d/1jsn0J6yRakfmvYcT1mZrFPdrp_nJI7wH/view?usp=sharing) (330 GB) contains all the video are a max of 360p resolution.

Alternative downloads:
[AViD_small_part1](https://indiana-my.sharepoint.com/:u:/g/personal/ajpiergi_iu_edu/EQJy9LbYiHROumzQbul9vCsBsYFyHtGIvtwnpFhjmFtIaQ?e=QRP2LR) 

[AViD_small_part2](https://indiana-my.sharepoint.com/:u:/g/personal/ajpiergi_iu_edu/EQ-z8s-6c7JMlA657mP6EYQBuFKB4vzqqShuVeUsPxB5ow?e=FvZPvG) 

[AViD_small_part3](https://indiana-my.sharepoint.com/:u:/g/personal/ajpiergi_iu_edu/Ea-WGKwTTzhNr4wTl3LhaHABQZ1TwptVCq_f_3QSuGoK1w?e=vRS5Zo)
