# YOLOv5-VS-YOLOr

YOLOR- You Only Learn One Representation is a machine learning/deep learning algorithm used for computer vision tasks mainly object detection. 
The YOLOR is a model that is faster and has higher accuracy when compared to that of the previously proposed models such as YOLOv4, Scaled YOLOv4 , Yolov5 , etc. All these models are proposed by the same author and are trained on the same dataset that is , the coco dataset. 

YOLOR is conceptually different from YOLO because it uses a unified network to encode implicit knowledge and explicit knowledge simultaneously. 
Explicit knowledge can be termed as any data that can be expressed in the written form and be understood in away such that certain conclusions could be drawn. These data are fact based and could be obtained using shallow neural networks.Conscious learning generates explicit knowledge.
Implicit knowledge can be defined as the detailed feature extraction from given data whereas explicit is rough feature extraction. Implicit knowledge can be obtained using deep neural networks.Subconscious learning generates implicit learning.

Both the models YOLOR and YOLOv5 were trained on the same dataset with the same hyper-parameters.

# Analysis:
System info: Ubuntu 20.04, GPU: Tesla T4, RAM: 12.68 GB

YOLOv5 inference time: 14 ms, FPS : 14

YOLOr inference time: 32 ms, FPS : 17
