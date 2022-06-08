# FlowerRecognition
## The Task
Project one in our course Artificial Intelligence is to create a model for Flower Recognition.

The data contains two folders: *train_data* and *test_data*. The *train_train* folder consists of 5486-images to use for training while the *test_data* folder contains 1351-images you can use to test your model in a **train-test-split** validation style.

There are two label files: *labels\train_labels.csv* and *labels\test_labels.csv*. Each file contains the filename of the corresponding image and the class label. In total we have **102 different classes** of flowers.

Due to the large number of images, there is a good chance that you can not easily fit the entire training and testing data into RAM. We therefore give you an implementation of a `DataGenerator` class that can be used with keras. This class will read in the images from your hard-drive for each batch during during or testing. The class comes with some nice features that could improve your training significantly such as **image resizing**, **data augmentation** and **preprocessing**.

## The Team
- Barış
- Edi
- Patrick
- Sascha
- Willi
