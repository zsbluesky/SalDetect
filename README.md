# The code for the joint learning of saliency prediction and object detection (using Faster RCNN).

## Usage
Please copy ```lib``` dir in [faster_rcnn.pytorch](https://github.com/jwyang/faster-rcnn.pytorch/tree/pytorch-1.0) to your ```root``` dir and install [faster_rcnn.pytorch](https://github.com/jwyang/faster-rcnn.pytorch/tree/pytorch-1.0), 
following the Preparation steps. Prepare the dataset of Pascal VOC according to [faster_rcnn.pytorch](https://github.com/jwyang/faster-rcnn.pytorch/tree/pytorch-1.0). Please prepare SALICON dataset according to [EML-Net](https://github.com/SenJia/EML-NET-Saliency).

## Training (Joint Learning) and Testing (Saliency Prediction)
Please refer to ```train2.py``` and ```test_net.py```. Change the predefined parameters according to your own data path, model path, etc. Here we do the joint 
learning of object detection and saliency prediction. While in the test stage, we only output saliency result. We use the Resnet50 backbone in the code.

## Acknowledgement
The code is based on [faster_rcnn.pytorch](https://github.com/jwyang/faster-rcnn.pytorch/tree/pytorch-1.0) and [EML-Net](https://github.com/SenJia/EML-NET-Saliency).
Hope the code is helpful for the joint learning in the field of saliency prediction.
