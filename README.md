# Team LeakyRelu: Ameya Akkalkotkar, Yogesh Riyat
Machine Learning, Computer Vision, Medical Imaging

This is a medical image classification project. 

The dataset contains ~85K retinal images with four classes - three disorders (CNV, DME, Drusen) and a Normal class (baseline).

Our objective is to label new retinal images with the appropriate disorder and generate corresponding heatmaps to highlight the relevant features that determine the pathology.

We used Xception as our model, and trained from scratch without weights for 1,000 epochs. 

We visualize our inference results by using a package called GradCAM. 

Both the model architecture and the GradCAM functions were developed by Francois Chollet from Google.

<img src="https://user-images.githubusercontent.com/6412336/182635421-38775d7a-0244-4009-848d-88394bdef1c9.jpg" width="250"/> <img src="https://user-images.githubusercontent.com/6412336/182636132-e6bd9118-5a94-48c5-8c84-f9a6d583b0a5.png" width="250"/>    
**_Here is a demonstration of GradCAM used in conjunction with a simple model trained on the CIFAR-10 data set_**


This is a work in progress and the next step for improving the accuracy of the GradCAM heatmaps would be to incorporate occlusion sensitivity into this pipeline.
