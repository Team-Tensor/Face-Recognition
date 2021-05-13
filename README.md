# Face-Recognition
CS419 Course Project: Team Tensor

## About the project:
*Dataset selected:*
* The Extended Yale Face Database B, Cropped Faces
* 39 subjects, grayscale with varying light conditions
* 2470 total images
* Since the cropped faces data was used, additional face detection is not needed

*Feature Extraction:* It is a dimensionality-reduction method that is often used to reduce the dimensionality of large data sets, by transforming a large set of variables into a smaller one that still contains most of the information in the large set. Analysis with a large number of variables generally requires a large amount of memory and computation power, also it may cause a classification algorithm to overfit to training samples and generalize poorly to new samples. 

*Feature Extraction Methods used:*
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

1. Install :
    
    If running on a local jupyter notebook, with Python 3:
    ```bash
    # With pip:
    pip install -r requirements.txt
    ```
    The [requirements.txt](requirements.txt) file has been included in this repository

    It is recommended to use the notebook in Google Colaboratory using the [link](https://colab.research.google.com/github/Team-Tensor/Face-Recognition/blob/main/CS419_project_final.ipynb) in [CS419\_Project\_Team-Tensor.ipynb](CS419_Project_Team-Tensor.ipynb)
    For running on Google Colab, all the libraries are pre-installed and can be imported directly.
    

2. Importing the CSV file of the unrolled and resized dataset:
   
   * The extraction code can be found in the section: "*Extracting images to arrays and saving to CSV*"
   * The CSV file is uploaded on drive, link to which is : [https://drive.google.com/file/d/1s4FNr6dPTrhh-mzevQQGeNgE5yjldQmg/view](https://drive.google.com/file/d/1s4FNr6dPTrhh-mzevQQGeNgE5yjldQmg/view)
   * Add a shortcut of the file to your own drive
   * Mount your drive to the colab project, found in the section: "*Using pre-extracted images from CSV file*"
        ```bash
        drive.mount('/content/gdrive')
        ```
   * Go to the requested url and authorize the request.

    
3. Importing the CSV file of the features extracted using the VGG16 model:
   
   * The extraction code can be found in the section: "*Generate features using VGG16 model*"
   * The CSV file is uploaded on drive, link to which is : [https://drive.google.com/file/d/1--pPvar9Jz8vCY5lpsdl6uJC4qFp4fvp/view?usp=sharing](https://drive.google.com/file/d/1--pPvar9Jz8vCY5lpsdl6uJC4qFp4fvp/view?usp=sharing)
   * Add a shortcut of the file to your own drive
   * Mount your drive to the colab project, found in the section: "*Using pre-extracted images from CSV file*"
        ```bash
        drive.mount('/content/gdrive')
        ```
   * Go to the requested url and authorize the request.
        
## A detailed report for the project can be found [here](Project-Report-Team-Tensor.pdf)

---

Project Authors: Atharva Raut, Akash Chodankar and Akshat Mehta
