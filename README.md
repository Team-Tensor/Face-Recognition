# Face-Recognition
CS419 Course Project: Team Tensor

## About the project:
*Dataset selected:*
* The Extended Yale Face Database B, Cropped Faces
* 39 subjects, grayscale with varying light conditions
* 2470 total images
* Since the cropped faces data was used, additional face detection is not needed

*Feature Extraction:* It is a dimensionality-reduction method that is often used to reduce the dimensionality of large data sets, by transforming a large set of variables into a smaller one that still contains most of the information in the large set. Analysis with a large number of variables generally requires a large amount of memory and computation power, also it may cause a classification algorithm to overfit to training samples and generalize poorly to new samples. Methods used:
* Principal component analysis (PCA)
* VGG16 model

*Regression and classification models used:*
* Logistic Regression
* Support vector machine
* Feed forward neural network
* Convolutional Neural Network (CNN)




## Table of contents:
* [Table of contents](#table-of-contents)
* [Quick start](#quick-start)


## Quick start

1. Install:
    
    ```bash
    # With pip:
    pip install facenet-pytorch
    
    # or clone this repo, removing the '-' to allow python imports:
    git clone https://github.com/timesler/facenet-pytorch.git facenet_pytorch
    
    # or use a docker container (see https://github.com/timesler/docker-jupyter-dl-gpu):
    docker run -it --rm timesler/jupyter-dl-gpu pip install facenet-pytorch && ipython
    ```
    
2. Importing the CSV file of the unrolled and resized dataset:
   
   * The extraction code can be found in the section: "*Extracting images to arrays and saving to CSV*"
   * The CSV file is uploaded on drive, link to which is : https://drive.google.com/file/d/1s4FNr6dPTrhh-mzevQQGeNgE5yjldQmg/view
   * Add a shortcut of the file to your own drive
   * Mount your drive to the colab project, found in the section: "*Using pre-extracted images from CSV file*"
        ```bash
        drive.mount('/content/gdrive')
        ```
   * Go the the requested url and authorize the request.

    
3. Importing the CSV file of the features extracted using the VGG16 model:
   
   * The extraction code can be found in the section: "*Generate features using VGG16 model*"
   * The CSV file is uploaded on drive, link to which is : https://drive.google.com/file/d/1--pPvar9Jz8vCY5lpsdl6uJC4qFp4fvp/view?usp=sharing
   * Add a shortcut of the file to your own drive
   * Mount your drive to the colab project, found in the section: "*Using pre-extracted images from CSV file*"
        ```bash
        drive.mount('/content/gdrive')
        ```
   * Go the the requested url and authorize the request.
        
