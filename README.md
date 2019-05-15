# Deep-Machine-Learning-for-Age-and-Gender-Prediction
This involves building and training Convolution Neural Network for predicting age and gender from an individual's image. Matlab Deep Learning Toolbox is used in Matlab environment. 
## Getting Started
Get this Repository to your local machine
```sh
git clone https://github.com/georgewanga/Deep-Machine-Learning-for-Age-and-Gender-Prediction.git
```
### Prerequisites
Into the cloned directory `Deep-Machine-Learning-for-Age-and-Gender-Prediction`, download and extract the Datasets.
 - [IMDB](https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/static/imdb_crop.tar) - Download IMDB faces only Datadet used
 - [WIKI](https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/static/wiki_crop.tar) - Download WIKI faces only Datadet used
 - [APPA-REAL](http://158.109.8.102/AppaRealAge/appa-real-release.zip) - Download APPA-REAL Datadet used

Ensure you have MATLAB R2018a or later releases installed.
Open the `AgeGenPredictCNN.mlx` script in matlab and ensure you adjust the working directory to current.
```
path/to/your/folder/Deep-Machine-Learning-for-Age-and-Gender-Prediction
```
## Running the tests
Run the script as from the `Load The Pretrained Network` downwards.
###### `WARNING!!` 
Running from the file top will mean Training.
##### Note 
- The sctipt can be run in sections.
- Use the `Predict Age and Gender` section to test
- Training requires Strong GPU capabilities
- Training on a CPU can cause the machine to freeze
- Train the network only if Neccessary

### Break down into end to end tests
#### Training
Run the entire script to train the network
Training will resume from checpoints created during the previous trainings.
To Avoid resuming and do a completely fresh training, navigate to the `data` folder and rename or delete the folder `trainCheckpoints` before running the file
#### Usage
Go to the script section `Load The Pretrained Network`
- run the two parts

Go to the script section `Predict Age and Gende`
- Run the single section
- You'll be prompted to choose a file
- Select an image with a face from your local machine
- The model will identify a face from your Image, add padding and crop it, then predict age and gender based on the detected face.

## Contributing
Please feel free to contribute to this code to make it better
## Authors

* **George Wanga** - *Initial work* 
[Linkedin](https://www.linkedin.com/in/wangageorge/)
[ORCID iD](https://orcid.org/0000-0002-4369-4626)
## Acknowledgments
In preparation of this work, I had to seek for help and guidance of some respected persons, who deserve my deepest gratitude. I would like to show my gratitude MR. SEGERA RENE DAVIES, Lecturer, at University of Nairobi for giving me a proper guidelines throughout numerous consultations. I would prefer to expand my feeling to all that have directly and indirectly guided me in putting this together.
