**Face Mask Detection**

**Architechture**
![alt text](https://github.com/shreyas-redij/Face_Mask_Detection/blob/master/Images/Faster_RCNN.JPG)

Faster R-CNN architecture contains 2 networks:

- Region Proposal Network (RPN)
- Object Detection Network

Region Proposal Network (RPN):
This region proposal network takes convolution feature map that is generated by the backbone layer as 
input and outputs the anchors generated by sliding window convolution applied on the input feature map.

Object Detection Network:
It  uses the RoI pooling layer for making region proposal of fixed size and 
twin layers of softmax classifier and the bounding box regressor is also used in the prediction of the object and its bounding box.

**Annotation**

We are suing LabelMe tool for annotating images
https://github.com/wkentaro/labelme
