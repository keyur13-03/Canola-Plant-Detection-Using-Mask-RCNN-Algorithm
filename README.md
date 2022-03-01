Mask RCNN works on a technique named 'Instance Segmentation'. Mask RCNN is the combination of two subproblems like object detection and semantic segmentation. For object detection, it uses Faster RCNN and generates bounding boxes and class probability. Mask RCNN uses a Fully Convolution Network to provide pixel to pixel binary mask on the region of interest generated by Faster RCNN that adds a small amount of computation cost only. Mask RCNN treats each object as an individual object whether they are in the same class or not.
