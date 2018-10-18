# Mask R-CNN for Object Detection and Segmentation

# Getting Started

```
conda env create -f env.yml

source activate mask_rcnn 

python setup.py install

mkdir data

python samples/coco/coco.py train --dataset=data/ --model=imagenet --download=True
```
