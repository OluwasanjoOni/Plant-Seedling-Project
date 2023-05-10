# Plant-Seedling-Project
## Objective
The Aarhus University Signal Processing group, in collaboration with the University of Southern Denmark, has provided the data containing images of unique plants belonging to 12 different species. Build a Convolutional Neural Network model which would classify the plant seedlings into their respective 12 categories.
## Data Description
This dataset contains images of unique plants belonging to 12 different species.
- The data file names are: 1. images.npy 2. Label.csv
- Due to the large volume of data, the images were converted to numpy arrays and stored in images.npy file and the corresponding labels are also put into Labels.csv so that you can work on the data/project seamlessly without having to worry about the high data volume.
- The goal of the project is to create a classifier capable of determining a plant's species from an image.
- List of Plant species
Black-grass
Charlock
Cleavers
Common Chickweed
Common Wheat
Fat Hen
Loose Silky-bent
Maize
Scentless Mayweed
Shepherds Purse
Small-flowered Cranesbill
Sugar beet
## Steps to follow
- Read the problem statement carefully 
- Download the dataset from the Olympus platform.
- Set runtime type to “GPU” in Google Colab, so that the code will run faster as you will be using CNN to fit your model.
- Install and import the required packages
- Load the dataset: firstly the "images.npy" and secondly the “Labels.csv" 
- Explore the dataset
- Visualise the images
- Carry Out data Pre-processing (Image normalisation)
- Before creating an object of the model, set a seed for reusability
- create an instant of the model and add the first layer
- Add as many hidden layers (Note that this is in form of hyper-parameter tunning)
- Add the output layer which is the fully connected layer
- Compile the model
- Train the model and evaluate the performance
## Conclusion
The model did not generalise well as the highest validation accuracy achieved was low comapared to the training accuracy.
