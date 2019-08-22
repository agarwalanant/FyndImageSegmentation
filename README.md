# FyndImageSegmentation

## Progress
1.Implemented R-CNN model but, it has the persisting problem of rough edges.


## TODO
1. GAN based implementation of the image segmentation model.

2. Generate a dataset with separate colour channels


## Approach
Started with pixel loss as it is the best performing techniques that have been implented so far.
focused and anlyzed why the pixel based model like MASK-RCNN fail to segment the minute details like hair and jwelries.

The problem I found was that the image is redused to lower resoltion for deep learing processing and minute details like hair and all loose their imprtance s pixel of these objects are reduced. 


So, I used the techniques used my Carien that I divided the image into several parts (size = model input size) rather than reducing the image resolution, there by preserving the details of the image.


A mojor flaw in the segmentation may be because of the multiple colout channels in the image.

> Split the image into different channels and apply image segmentarion on that -> combine the image (min of each image)
