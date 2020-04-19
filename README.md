# dog-breed-classifier

The aim of the project is to build a pipeline to process real-world, user-supplied images. The algorithm will identify an estimate of the dog’s breed given an image. When the image is of a human, the algorithm will choose an estimate of a dog breed that resembles the human. If neither a dog or a human is detected, then an error message is output. Therefore, the models in place should be capable of detecting a dog or human in an image, classify the dog to its breed and classify a dog breed that the human resembles.


## Datasets

The dataset used here are provided by Udacity and is similar to Kaggle Dog Breek Classifier Dataset.The dataset is saved under S3 in Amazon Web Service.

This link [https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip] provides the images for human and can be used to train a human face detector.

This link [https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip] provides the images for dog and can be used to training of dog related model .


## Main Kaggle Competition link :
Dog Breed Identification (https://www.kaggle.com/c/dog-breed-identification)
