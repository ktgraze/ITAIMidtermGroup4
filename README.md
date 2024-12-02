# ITAI-1378 Midterm - Object Detection Challenge Group 4
### Overview
For the Midterm project, we chose to work with the **Oxford-IIIT Pet Dataset** to train an object detection model to accurately predict one of 37 classes.
After performing Exploratory Data Analysis, we normalized, resized, and one-hot encoded the images. 
We then set up an ImageDataGenerator to augment our images. After experimenting with the MobileNetV2 model, we had better results with the **VGG16 model**.
Lastly, we fine-tuned the model experimenting with freezing different layers.
