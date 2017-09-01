# Vehicle detection using image segmentation
In this project, We used annotated vehicle data set provided by Udacity: https://github.com/udacity/self-driving-car/tree/master/annotations. Then I trained a scaled down version of U-Net architecture. The input to U-net is a resized 960X640 3-channel RGB image and output is 960X640 1-channel mask of predictions. I trained the network on my laptop and it takes too long. By improving the network and using more powerful GPU, we can get better results. 

Youtube link of result:

https://www.youtube.com/watch?v=KiaB68I0kvo&feature=youtu.be

You can download dataset from here : https://github.com/udacity/self-driving-car/tree/master/annotations

There are some useful links which I used:

https://github.com/jocicmarko/ultrasound-nerve-segmentation

https://github.com/vxy10/p5_VehicleDetection_Unet

https://handong1587.github.io/deep_learning/2015/10/09/segmentation.html
