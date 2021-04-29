# Transfer_Learning-Fine_Tuning_Using_VGG16-ResNet50-MobileNet-Inception_V3
In this notebook, I use 4 CNNs to train my own classifier to distinguish between Watermelons, Tomato and Pumpkin using Transfer Learning and Fine Tuning along with Data Augmentation.

Here's a metric summary of our models and their respective error rates on our 3 class classification task:
1) VGG16 - Using only Transfer Learning - Errors: 15/150
1.1) VGG16 - Freezing all but last 4 Layers of CNN w/o Data Augmentation - Errors: 9/150
1.2) VGG16 - Freezing all but last 4 Layers of CNN with Data Augmentation - Errors: 4/150

2) ResNet50 - Only Transfer Learning - Errors: 43/150
2.1) ResNet50 - Freezing all but Last 4 Layers with Data Augmentation - Errors: 39/150

3) MobileNet - Only Transfer Learning - Errors: 34/150
3.1) MobileNet - Freezing all but Last 3 Layers with Data Augmentation: Errors: 3/150

4) Inception_V3 - Only Transfer Learning - Errors: 61/150
4.1) Inception_V3 - Using Data Augmentation - Errors: 2/150
