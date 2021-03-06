---
layout: page
title: Publications
permalink: /pub/
published: true
---

## My Papers

**Deep Watershed Detector for Music Object Recognition**
<div style="padding: 0px; background-color: Gainsboro; width: 1000px;display: table;">
    <span style="vertical-align: middle; display: table-cell;">
    <img style="vertical-align: middle; display: table-cell; margin-right: 1em;" src="{{site.baseurl}}/overlayed.png"  width="2000"  />
    </span>
<span style="vertical-align: middle; display: table-cell; padding: 5px; font-size: 15px;">
Optical Music Recognition (OMR) is an important and challenging area within music information retrieval, the accurate detection of music symbols in digital images is a core functionality of any OMR pipeline. In this paper, we introduce a novel object detection method, based on synthetic energy maps and the watershed transform, called Deep Watershed Detector (DWD). Our method is specifically tailored to deal with high resolution images that contain a large number of very small objects and is therefore able to process full pages of written music. We present state-of-the-art detection results of common music symbols and show DWD's ability to work with synthetic scores equally well as with handwritten music.
</span>
</div>
To appear at [ISMIR 2018](http://ismir2018.ircam.fr/)    
[Tech Report]({{site.baseurl}}/papers/DWD_preprint.pdf)  










**DeepScores -- A Dataset for Segmentation, Detection and Classification of Tiny Objects** 
<div style="padding: 0px; background-color: Gainsboro; width: 1000px;display: table;">
    <span style="vertical-align: middle; display: table-cell;">
    <img style="vertical-align: middle; display: table-cell; margin-right: 1em;" src="{{site.baseurl}}/ds_overview.png"  width="3500"  />
    </span>
<span style="vertical-align: middle; display: table-cell; padding: 5px; font-size: 15px;">
We present the DeepScores dataset with the goal of advancing the state-of-the-art in small object recognition by placing the question of object recognition in the context of scene understanding. DeepScores contains high quality images of musical scores, partitioned into $300,000$ sheets of written music that contain symbols of different shapes and sizes. With close to a hundred million small objects, this makes our dataset not only unique, but also the largest public dataset. DeepScores comes with ground truth for object classification, detection and semantic segmentation. DeepScores thus poses a relevant challenge for computer vision in general, and optical music recognition (OMR) research in particular. We present a detailed statistical analysis of the dataset, comparing it with other computer vision datasets like PASCAL VOC, SUN, SVHN, ImageNet, MS-COCO, as well as with other OMR datasets. Finally, we provide baseline performances for object classification, intuition for the inherent difficulty that DeepScores poses to state-of-the-art object detectors like YOLO or R-CNN, and give pointers to future research based on this dataset.
</span>
</div>  
To appear at [ICPR 2018](http://www.icpr2018.org/)     
[Tech Report]({{site.baseurl}}/papers/preprint_deepscores.pdf)  
 
## Co-Authorships
**DeepScores and Deep Watershed Detection: current state and open issues**
<div style="padding: 0px; background-color: Gainsboro; width: 1000px;display: table;">
    <span style="vertical-align: middle; display: table-cell;">
    <img style="vertical-align: middle; display: table-cell; margin-right: 1em;" src="{{site.baseurl}}/scan.png"  width="1000px"  />
    </span>
<span style="vertical-align: middle; display: table-cell; padding: 5px; font-size: 15px;">
This paper gives an overview of our current Optical Music Recognition (OMR) research. We recently released the OMR data set DeepScores  as well as the object detection method Deep Watershed Detector. We are currently taking some additional steps to improve both of them. Here we summarize current and future efforts, aimed at improving usefulness on real-world tasks and tackling extreme class imbalance.
</span>
</div>  
To appear at [WoRMS 2018](https://sites.google.com/view/worms2018)  
[Tech Report]({{site.baseurl}}/papers/WoRMS_preprint.pdf)  
