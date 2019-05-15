# Deep-Machine-Learning-for-Age-and-Gender-Prediction
Deep learning belongs to Machine Learning Which Belongs to Artificial Intelligence. This project involves using Convolution Neural Network, in Matlab Deep Learning Toolbox, to built and train the CNN for predicting age and gender from an individual's image
#The Construction of the Method
The CNN is initially built so as to copy a brain. This model divides age and gender into two further problems. The inputs to these two is given through an image. The CNN outputs labels around the faces showing the age and gender output.
# The CNN Model
This has multiple layers. The input layer takes a 224×224 image with three channels. Multiple convolution layers are used with Batch Normalization, Pooling and activation function. Batch Normalization is used to make values range from 0 to 1 instead of 0 to 255, this increases the efficiency of the model. The pooling layer reduces the redundancy of the model, this reduces the unimportant features and only gives the important ones, from the filter map. 
#The Sample
The  IMDB-WIKI dataset is used. It is the largest publicly available dataset of face images with gender and age labels for training. APPA-REAL Dataset containing 7,591 images with associated real and apparent age labels is then used to enhance accuracy as it has more clear images
#Details of Data Pre-processing 
Deep learning requires large Datasets which is provided by the IMDB WIKI and APPA-REAL Datasets. 
When inspecting the data, most of the photos don't make sense for the age to which they are set, some are not readable and some do not have faces. Therefore, learning something reliable from such data seems impossible for the network. 
It becomes necessary to clean the data before using it.
# My Results
Even though the gender prediction network performed well, the age prediction network fell in need of my expectation. I attempted to search out the solution and noted that a lot of training is to be done to improve on the accuracy. 
Apart from this, I have a tendency to think that the accuracy of the models can be improved by employment of face alignment and introduction of some reasonable padding around it before passing it into the network for prediction.
I additionally analysed the employment of face detection before creating predictions and noted that the predictions improved for a few samples while becoming worse for some other images. Proper detection and alignment are necessary if you are mainly operating with non-frontal faces.
Gender accuracy goes as high as 80% since there is only two possible and very distinct outcome. This is not true for Age at 1%, for example it would be difficult to sport age difference between two individuals who are 25 and 26 years old or say 80 and 81 years old, this CNN finds this hard too, just as human brain, therefore may miss the exact figure of a person’s age. These percentages are determined on precision thus the closeness to a given age is ignored. This makes the age prediction to even be much lower as predicting an age of 45 instead of actual 46 is considered inaccurate.
Overly, I believe the accuracy of the models are good, however, it can be improved more by exploitation additional data, defining more data augmentation and improving to higher network architectures
