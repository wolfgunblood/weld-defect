# weld-defect

weld-defect detection
This a project on automatic detection of weld defects using machine learning

Convulational Neural Network is used to detect different welding defects.

Welding Defects generally have different structures like in porosity defect pores are formed due to trapped gases and in over spattering, there are metal particles from the weld that is stuck on the area adjacent to the weld area. The welding defects can be automatically detected using image classification and convolution neural network.

In order to use CNNs, we need to have a well-segregated dataset of welding defects images. So far I have collected 61 images of welding defects. I have edited and selected the images that can be used for detection. I have separated the images in the following categories : - Good Weld image Porosity Over Spatter Burn Through Undercut OverLap

Tensorflow and Keras are imported to implement the CNNs.
