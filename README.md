#### Use FCOS+deepsort and yoloV3+deepsort

##### Pedestrian detection

The experiment was trained on 40,000 data sets, and 40,000 iterations were performed. 
The test MAP used 15,360 images


Model    |   MAP
-------- | ---------
 YOLO-V3-tiny |    42%
YOLO-V3+GIOU  |   62.5%
 YOLO-V3+Soft-NMS |   65.7%
 FCOS-ResNet50   |   65.38%(5 epoch)
 FCOS-mobilenet v2 |  75% (90000 iters)
 
 
[![Watch the video](https://raw.github.com/GabLeRoux/WebMole/master/ressources/WebMole_Youtube_Video.png)](https://youtu.be/qaVJYk5gIVs)