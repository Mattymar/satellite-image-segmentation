# satellite-image-segmentation
This was my final project at the Metis Data Science Bootcamp. It was done as part of a partnership with Digital Globe, utilizing images from their WorldView-3 satellite to perform image segmentation.

## Project Goal

In my project, I performed image segmentation on satellite imagery from Shanghai in an attempt to map out the location of farmland. In the course of the project, I was able to extend to segmenting multiple classes, but for the purposes of the presentation, my focus was on farmland.

<img src="https://github.com/Mattymar/satellite-image-segmentation/blob/master/images/farmland1.png" width=256> <img src="https://github.com/Mattymar/satellite-image-segmentation/blob/master/images/farmland2.png" width=256> <img src="https://github.com/Mattymar/satellite-image-segmentation/blob/master/images/farmland3.png" width=256>

I decided to map out farmland in Shanghai because I feel it highlights a powerful aspect of satellite image segmentation. It gives us the ability to track changes in critical changes in environment and landscape over time. As a city that used to be surrounded by farmland, which has exploded in population in recent years, Shanghai was a natural city to begin my exploration.

## Workflow

To accomplish my objective, I had to:

1. Locate images containing farmland using Open Street Maps data.
2. Create ground truth masks using QGIS.
3. Train several convolutional neural networks to predict the segmentation.
4. (Optionally) ensemble model predictions.

The models used are available in this github repository.

## Some Segmentation Results

<img src="https://github.com/Mattymar/satellite-image-segmentation/blob/master/images/results1b.png" width=820>

| <img src="https://github.com/Mattymar/satellite-image-segmentation/blob/master/images/results2a.png" width=256> | <img src="https://github.com/Mattymar/satellite-image-segmentation/blob/master/images/results2b.png" width=256> | <img src="https://github.com/Mattymar/satellite-image-segmentation/blob/master/images/results2c.png" width=256>