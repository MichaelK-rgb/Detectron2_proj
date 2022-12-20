# Detectron2 for Panoptic segmentation, image pre-processing and Object detection
This project's goal is to use Detectron2 for segmentation and cropping of the skyline before detecting objects in an image Dataset.

Example images from the COCO dataset images:

![image](https://user-images.githubusercontent.com/65919086/208775988-b03cf3e1-d76f-4399-bcd4-59d065cb63e6.png)                       ![image](https://user-images.githubusercontent.com/65919086/208775939-8bab37a7-bc7c-44b8-96e7-bd356b428372.png)

The goal of this project: Modify the example dataset such that the image is cropped at the lowest skyline: using panoptic segmentation for the 'sky' category it is possible to locate the lowest pixel that is segmented as a part of the sky in each image.

![image](https://user-images.githubusercontent.com/65919086/208776873-529d8f50-37f3-43af-b28f-b063218ca58f.png)

The collab notebook contains exploration and visualization of the process to the end result, as well as some exploration:

![image](https://user-images.githubusercontent.com/65919086/208777021-eebc5339-76d8-4ef9-afbb-7f9dab3364db.png)
![image](https://user-images.githubusercontent.com/65919086/208777040-b0401f21-cbe4-429b-b18c-fc01921b84e7.png)

average sky area in images is 52318.2 pixels, and average lowest skyline height is 123.2 pixels. (when normalized to 480*640)

![image](https://user-images.githubusercontent.com/65919086/208778848-df61da11-d782-4433-9154-a254ec364106.png)

