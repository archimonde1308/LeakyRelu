# Team leaky-relu: Ameya Akkalkotkar, Yogesh Riyat
Machine Learning, Computer Vision, Medical Imaging

This is a medical image classification project. 

The dataset contains ~85K retinal images with four classes - three disorders (CNV, DME, Drusen) and a Normal class (baseline).

Our objective is to label new retinal images with the appropriate disorder and generate corresponding heatmaps to highlight the relevant features that determine the pathology.

We used Xception as our model, and trained from scratch without weights for 1,000 epochs. 

We visualize our inference results by using a package called GradCAM. 

Both the model framework and the GradCAM functions were developed by Francois Chollet from Google.
