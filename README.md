# 42028-YOLOX-Colaboratory-Training

This is a colab tutorial to train [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) on Google Colaboratory<br>
It includes the following contents.<br>
* Sample Aquarium Data set (Annotation not implemented)
* Sample Aquarium Data set (Annotated)
* Colaboratory notebook (environment setting, model training)

# Requirements
* Pytorch 1.9.0 or later
* apex 0.1 or later
* pycocotools 2.0 or later
* OpenCV 3.4.2 or later
* onnxruntime 1.5.2 or later ※Only when performing inference samples

# About annotation
It is assumed that annotation data is in Pascal VOC format.<br>
However, it is further converted to MS COCO format in the notebook.<br><br>

**You may modify the code to use your dataset in COCO format if required.**

The notebook sample assumes the following directory structure.<br>
However, since "pascal_label_map.pbtxt" is not used in this sample, <Br>
There is no problem even if you do not store it.
```
02.annotation_data
│  000001.jpg
│  000001.xml
│  000002.jpg
│  000002.xml
│   :
│  000049.jpg
│  000049.xml
│  000050.xml
└─ pascal_label_map.pbtxt
  
```

# Usage
[![Use Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com)<br>
Training will be performed on Google Colaboratory.<br>

# Author
[Gitarth Vaishnav](https://linkedin.com/in/gitarthvaishnav)

# License 
42028_YOLOX is under [Apache-2.0 License](LICENSE).
