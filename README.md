[![Skylab Research](skylab-research.png)](https://research.skylabtech.ai/)

# Flickr-Faces-HQ-Retouching (FFHQR) Dataset

![License CC](https://img.shields.io/badge/license-CC-green.svg?style=plastic)
![Format PNG](https://img.shields.io/badge/format-PNG-green.svg?style=plastic)
![Resolution 1024&times;1024](https://img.shields.io/badge/resolution-1024&times;1024-green.svg?style=plastic)
![Images 70000](https://img.shields.io/badge/images-70,000-green.svg?style=plastic)
![Teaser image](./ffhqr-teaser.jpg)

- [Flickr-Faces-HQ-Retouching (FFHQR) Dataset](#flickr-faces-hq-retouching-ffhqr-dataset)
  - [Licenses](#licenses)
  - [Overview](#overview)
  - [Acknowledgements](#acknowledgements)
  - [Privacy](#privacy)

Flickr-Faces-HQ-Retouching (FFHQR) is a high-quality image dataset of retouched human faces. The dataset is released as part of the following paper:

> **AutoRetouch: Automatic Professional Face Retouching**<br>
> Alireza Shafaei ([skylabtech](https://research.skylabtech.ai)), James J. Little (UBC), Mark Schmidt (UBC)<br>
> Winter Conference on Applications of Computer Vision (WACV), 2021<br>
> • [WACV 21 Page](https://openaccess.thecvf.com/content/WACV2021/html/Shafaei_AutoRetouch_Automatic_Professional_Face_Retouching_WACV_2021_paper.html)
> • [PDF](https://openaccess.thecvf.com/content/WACV2021/papers/Shafaei_AutoRetouch_Automatic_Professional_Face_Retouching_WACV_2021_paper.pdf)
> • [Supp](https://openaccess.thecvf.com/content/WACV2021/supplemental/Shafaei_AutoRetouch_Automatic_Professional_WACV_2021_supplemental.pdf)
> • [Video](https://youtu.be/NBFkSL5XhHA) •

The [original FFHQ dataset](https://github.com/NVlabs/ffhq-dataset) consists of 70,000 1 MP face-aligned images that are collected from Flickr. We professionally retouched FFHQ to create FFHQR. FFHQR is the first large-scale publicly available retouching dataset. We chose FFHQ as the basis of our new dataset because of the variety of ages, ethnicity, lighting conditions, and the large number of images that could benefit from face retouching.

For press, business, and other inquiries, please contact [alireza@skylabtech.ai](mailto:alireza@skylabtech.ai)

## Licenses

- The original FFHQ license is available [here](https://github.com/NVlabs/ffhq-dataset).
  - The individual images may have the following licenses: [Creative Commons BY 2.0](https://creativecommons.org/licenses/by/2.0/), [Public Domain Mark 1.0](https://creativecommons.org/publicdomain/mark/1.0/), [Creative Commons BY-NC 2.0](https://creativecommons.org/licenses/by-nc/2.0/), [Public Domain CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/), [U.S. Government Works](http://www.usa.gov/copyright.shtml).
  - According to the FFHQ homepage, "all of these licenses allow **free use, redistribution, and adaptation for non-commercial purposes**. However, some of them require giving **appropriate credit** to the original author, as well as **indicating any changes** that were made to the images."

The retouching dataset is made available under [Creative Commons BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) license by [Skylab Technologies Incorporated](https://skylabtech.ai). You can **use, redistribute, and adapt it for non-commercial purposes**, as long as you (a) give appropriate credit by **citing our paper**, (b) **indicate any changes** that you've made, and (c) distribute any derivative works **under the same license**.

```bibtex
@InProceedings{Shafaei_2021_WACV,
    author    = {Shafaei, Alireza and Little, James J. and Schmidt, Mark},
    title     = {AutoRetouch: Automatic Professional Face Retouching},
    booktitle = {Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)},
    month     = {January},
    year      = {2021},
    pages     = {990-998}
}
```

## Overview

To use FFHQR, you first need to [download the original 1024x1024 FFHQ images](https://github.com/NVlabs/ffhq-dataset).

The retouched images (`FFHQR`) can be downloaded below.

| Path | Size | Files | Format | Description |
| :--- | :--: | ----: | :----: | :----------
| ffhqr-dataset |  |  | |
| &boxvr;&nbsp; [images1024x1024 - part 1](https://www.cs.ubc.ca/~shafaei/dataset/ffhqr.part1.tar) | 13 GB | 10,000 | PNG (tar package) | 00000-09000
| &boxvr;&nbsp; [images1024x1024 - part 2](https://www.cs.ubc.ca/~shafaei/dataset/ffhqr.part2.tar) | 13 GB | 10,000 | PNG (tar package) | 10000-19000
| &boxvr;&nbsp; [images1024x1024 - part 3](https://www.cs.ubc.ca/~shafaei/dataset/ffhqr.part3.tar) | 13 GB | 10,000 | PNG (tar package) | 20000-29000
| &boxvr;&nbsp; [images1024x1024 - part 4](https://www.cs.ubc.ca/~shafaei/dataset/ffhqr.part4.tar) | 13 GB | 10,000 | PNG (tar package) | 30000-39000
| &boxvr;&nbsp; [images1024x1024 - part 5](https://www.cs.ubc.ca/~shafaei/dataset/ffhqr.part5.tar) | 13 GB | 10,000 | PNG (tar package) | 40000-49000
| &boxvr;&nbsp; [images1024x1024 - part 6](https://www.cs.ubc.ca/~shafaei/dataset/ffhqr.part6.tar) | 13 GB | 10,000 | PNG (tar package) | 50000-59000
| &boxvr;&nbsp; [images1024x1024 - part 7](https://www.cs.ubc.ca/~shafaei/dataset/ffhqr.part7.tar) | 13 GB | 10,000 | PNG (tar package) | 60000-69000
| &boxur;&nbsp; [thumbnails128x128](https://www.cs.ubc.ca/~shafaei/dataset/thumbs.tar) | 2.3 GB | 70,000 | PNG (tar package) | Thumbnails at 128&times;128

- Data Split (by folders):
  - Train: `00000` to `55000`
  - Validation: `56000` to `62000`
  - Test: `63000` to `69000`

## Acknowledgements

We would like to thank the [PhotoRetouchOnline.com](http://PhotoRetouchOnline.com) team and the [Artona Group Inc.](https://www.artona.com/) staff for their valuable feedback and support. We thank Tero Karras (NVIDIA), Samuli Laine (NVIDIA), Timo Aila (NVIDIA) for the original FFHQ dataset.

## Privacy

If you wish to remove a photo that you own from FFHQ and FFHQR, please follow the [FFHQ instructions](https://github.com/NVlabs/ffhq-dataset#privacy). After your image is successfully deleted from FFHQ, please contact `alireza@skylabtech.ai` to remove the corresponding image from FFHQR.
