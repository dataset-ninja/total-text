**Total-Text** is a dataset tailored for instance segmentation, semantic segmentation, and object detection tasks, containing 1555 images with 11165 labeled objects belonging to a single class — *text* with ***text** label tag. Its primary aim is to open new research avenues in the scene text domain. Unlike traditional text datasets, Total-Text uniquely includes curved-oriented text in addition to horizontal and multi-oriented text, offering diverse text orientations in more than half of its images. This variety makes it a crucial resource for advancing text-related studies in computer vision and natural language processing.

The effort of collecting this dataset is motivated by the missing of curved text in existing scene text datasets. Curved text can be easily found in real life scenes such as: business logos, signs,  entrances etc, surprisingly such data has close to zero existence in the current datasets. The most popular scene text dataset over the decade, [ICDARs]() have only horizontal text.

Authors propose Total-Text with 4,265 curved text out of 9,330 total text instances, hoping to spur an interest in the community to address curved text.

<img src="https://i.ibb.co/hZP3R3f/d234c946ce55.jpg" alt="image" width="800">

<span style="font-size: smaller; font-style: italic;">Statistics of Total-Text dataset.</span>

## Curved text observation

Geometrically speaking, a straight line has no angle variation along the line, and thus can be described as a linear function, <i>y = mx + c</i>. A curved line is not a straight line. It is free of angle variation restriction throughout the line. Shifting to the scene text perspective, authors observed that horizontal oriented text or word is a series of characters that can be connected by a straight line; their bottom alignment in particular for most cases. At the same time, multi-oriented text, in scene text convention, can also be connected by a straight line, given an offset with respect to a horizontal line. Meanwhile, characters a in curved word will not have unified angle offset, in which deemed to fit a polynomial line in text
level. 

<img src="https://i.ibb.co/xzymvzf/208d9bb2f90f.jpg" alt="image" width="800">

<span style="font-size: smaller; font-style: italic;">1st row: Examples from ICDAR 2013, ICDAR2015 and MSRA-TD500; 2nd row: Slightly curved to extremely curved text examples from the Total-Text.</span>

In authors' dataset collection, they found out that curved text in natural images could vary from slightly curved to extremely curved. Also, it is not surprising to find that most of them are in the shape of a symmetric arc due to the [symmetrical preferences in human vision](21).

## Orientation diversity

Approximate by half of the text instances are curved, and the other half is split almost equally between horizontal and multi-oriented. Curve text has its own variation too. Based on authors' observation, they classified them as horizontal curved, vertical curved, circular, and wavy (refer to 6a for image example). A lthough all the images were collected with curved text in mind, other orientations still occupy half of the total instances. A closer look into the dataset shows that curved text usually appears with either horizontal or multi-oriented texts. The mixture of orientations in an image, challenges text detection algorithms to achieve robustness and generalization in terms of text orientations.

## Scene diversity

In comparison to CUTE80 (the only publicly available curved text dataset), which majority of the images are football jerseys, Total-Text is much more diversified. Business related places like restaurant (i.e., Nandos, Starbucks), company branding logos, and merchant stores take up of 61.2% of the curved text instances. Tourist spots such as park (i.e., Beverly Hills in America), museums and landmarks (i.e., Harajuku in Japan) occupy 21.1%. 

<img src="https://i.ibb.co/0nH471S/f60acb3d7d63.jpg" alt="image" width="800">

<span style="font-size: smaller; font-style: italic;"> Curved text is commonly seen in real world scenery.</span>
