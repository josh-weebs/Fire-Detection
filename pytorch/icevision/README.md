## IceVision
* Recommended on fastai forum to checkout [IceVision](https://github.com/airctic/icevision) for object detection with custom training
* IceVision is an Object-Detection Framework that connects to different libraries/frameworks such as Fastai, Pytorch Lightning, and Pytorch with more to come.
* Worked through getting started guide with no issues. Can use exact notebook for fine tuning on fire dataset
* First step is [loading the dataset](https://github.com/airctic/icedata#coco-and-voc-compatible-datasets) which is in (Pascal);/ VOC format
* Article comparing the models available in IceVision -> https://medium.com/geekculture/different-models-for-object-detection-9c5cda7863c1

## Model results comparison
Interestingly all models plateau around COCOMetric 0.3
- retinanet: plateaus around 0.27
- efficientdet_tf_lite0: at 100 epochs 0.32
- faster_rcnn: plateaus around 0.33
- yolo5: at 100 epochs 0.35