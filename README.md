# Team LeakyRelu: Ameya Akkalkotkar, Yogesh Riyat
Machine Learning, Computer Vision, Medical Imaging

This is a medical image classification project. 

The dataset contains ~85K retinal images with four classes - three disorders (CNV, DME, Drusen) and a Normal class (baseline).

Our objective is to label new retinal images with the appropriate disorder and generate corresponding heatmaps to highlight the relevant features that determine the pathology.

We used Xception as our model, and trained from scratch without weights for 1,000 epochs. 

We visualize our inference results by using a package called GradCAM. 

Both the model architecture and the GradCAM functions were developed by Francois Chollet from Google.

This is a work in progress and the next step for improving the accuracy of the GradCAM heatmaps would be to incorporate occlusion sensitivity into this pipeline.

![cat_example](https://user-images.githubusercontent.com/6412336/182632494-9616b666-6b22-4eb6-bbbb-d70dd924ccb5.jpg width="200" height="200") ![grad_cam](https://user-images.githubusercontent.com/6412336/182632498-e1cf0d45-25d6-489f-b53f-dbc2b1fcd48e.png width="200" height="200")
