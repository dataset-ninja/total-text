**Total-Text** is a dataset for instance segmentation, semantic segmentation, and object detection tasks. It is used in the optical character recognition (OCR) domain. 

The dataset consists of 1555 images with 11165 labeled objects belonging to 1 single class (*text*).

Images in the Total-Text dataset have pixel-level instance segmentation annotations. Due to the nature of the instance segmentation task, it can be automatically transformed into a semantic segmentation (only one mask for every class) or object detection (bounding boxes for every object) tasks. There are 300 (19% of the total) unlabeled images (i.e. without annotations). There are 2 splits in the dataset: *train* (1255 images) and *test* (300 images). Also the dataset includes ***text*** object tag. Explore them in supervisely advanced labeling tool. The dataset was released in 2017 by the University of Malaya, Malaysia.

<img src="https://github.com/dataset-ninja/total-text/raw/main/visualizations/poster.png">
