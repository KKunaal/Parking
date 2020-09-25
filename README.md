# Real-time image-based parking occupancy detection and automatic parking slot deliniation usingdeep learning: A tutorial
This is the MATLAB tutorial of our upcoming Book Chapter (will update the details soon). We provide a MATLAB [Live Script] (https://github.com/DebadityaRMIT/Parking/blob/master/FinalCode.mlx)

(.mlx file), and the corresponding PDF document for convinience. 

There are two tutorials that are presented to obtain results on a sample dataset that we publically share at (https://rmit.figshare.com/ndownloader/files/24753887). The first tutorial involves fine-tuning a pre-trained deep neural network for vehicle detection in a sequence of CCTV camera images to determine the occupancy of the parking spaces. Also, we provide insights on the training hyper-parameters, training and testing times, accuracies and visualise some wrong classifications.

In the second tutorial, we perform spatio-temporal analysis of the detections made by Faster-RCNN for automatic parking slot delineation. We combined the detections in multiple frames and performed spatio-temporal analysis of the parking slots to automatically delineate the parking slots. We used a robust density-based clustering algorithm to find the centre of the parking slots, and then weighted the bounding boxes according to the detection scores (confidence). We further post-processed the delineations to improve the detection accuracy.

