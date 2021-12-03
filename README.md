## Evaluation of Detection and Segmentation Tasks on Road Scene Datasets
------------
The repository for our paper titled: *Evaluation of Detection and Segmentation Tasks on Road Scene Datasets*

**Authors**:  Deepak Singh<sub>1</sub>,  Ameet Rahane<sub>2</sub>,  Ajoy Mondal<sub>1</sub>, Anbumani Subramanian<sub>3</sub>,  C. V. Jawahar<sub>1</sub>
<sup>1</sup>International Institute of Information Technology, Hyderabad, India <sup>2</sup>University of California, Berkeley,  <sup>3</sup>Intel, Bangalore, India

To be presented at CVIP, 2021 (Oral)

------------
<p align="center">
    <img src="https://github.com/deepakksingh/Eval_of_Det_and_Seg_Tasks/blob/main/res/github_cvip_readme.png">
</p>



------------
#### Abstract
Object detection, semantic segmentation, and instance segmentation form the bases for many computer vision tasks in autonomous driving. The complexity of these tasks increases as we shift from object detection to instance segmentation. The state-of-the-art models are evaluated on standard datasets such as PASCAL-VOC and MS-COCO, which do not consider the dynamics of road scenes. Driving datasets such as Cityscapes and Berkeley Deep Drive BDD) are captured in a structured environment with better road markings and fewer variations in the appearance of objects and background. 

However, the same does not hold for Indian roads. The Indian Driving Dataset (IDD) is captured in unstructured driving scenarios and is highly challenging for a model due to its diversity. This work presents a comprehensive evaluation of state-of-the-art(SOTA) models on object detection, semantic segmentation, and instancesegmentation on-road scene datasets. We present our analyses and compare their quantitative and qualitative performance on structured driving datasets (Cityscapes and BDD) and the unstructured driving dataset(IDD); understanding the behavior on these datasets helps in addressing various practical issues and helps increating real-life applications.

---
#### Prerequisities
- To setup the framework, follow the steps of INSTALL.md
- All configs of :
    - *object detection* models are present in *configs/config_od*.
    - *semantic segmentation* models are present in *configs/config_ss*.
    - *instance segmentation* models are present in *configs/config_is*.
---
##### Models evaluated:
| Object Detection Models  |  Semantic Segmentation | Instance Segmentation   | Datasets|
| ------------ | ------------ | ------------ | ------------ |
|Faster-RCNN, SSD, RetinaNet, YOLOv3   | PSPNet, ERFNet, DRN   | Mask-R-CNN, Cascade R-CNN,  MS R-CNN  | Citscapes, IDD, BDD

---
#### Acknowledgement:
Our evaluation are performed on top of Detectron2 and mmdetection libraries.

---
#### Citation:
If you find our work useful in your research, please cite us.



