# Malaria_classifier
Classify Malaria infected cells using computer vision and neural network.
Implemented with Keras, using tensorflow as backend.

### Pre-requisites
1. OpenCV
2. Keras
3. matplotlib
4. tqdm

### To Run the Notebook  

Download the dataset from https://ceb.nlm.nih.gov/proj/malaria/cell_images.zip extract and place it in a folder named cell_images

I renamed the directories and kept some images (about 1000) aside in a "Test" folder for later testing. The following is the file structure of cell_images folder:  
```
.
└── cell_images
    ├── Test
    │   ├── infected
    │   └── uninfected
    └── Train
        ├── infected
        └── uninfected
 
```

As long as cell_images and Classifier.ipynb are in same directory, there is no need to edit any path in the code. 
Run the code, and Enjoy! :)
