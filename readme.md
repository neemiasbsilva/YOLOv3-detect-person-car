# Using YOLO (You Only Look Once) object detection algorithm to detect persons and cars

<p align="center"><img src="person-car.jpg" width="45%" height="45%"></p> 
<h6 align="center">Person and car in London [<a href="https://unsplash.com/photos/AvHBdfZ0HAQ">Vereinigtes Königreich</a>.</h6>

## Overview

YOLO can view an image and draw bounding over what it perceives as identified classes. We apply a single neural network to the full image. This network divedes the image into regions and predicts bounding boxes and probabilities for each region. These bounding boxes are weighted by the predicted probabilities. For more information about this algorithm, please, [click here](https://arxiv.org/abs/1804.02767).




