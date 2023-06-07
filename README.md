# Face Recognition
This is a project where face recognition using CNNs is done for 30 actors in the [IMDB-WIKI dataset](https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/). From this dataset, I only used the actors in the IMDB dataset and not in Wikipedia. More specifically, I extracted at least 25 colored images for 30 actors from the imdb_8.tar subset of the IMDB dataset. 
All of the images used for these 30 actors (15 male and 15 female of varying skintones) were stored in the _train_, _valid_ and _test_ folders on my Google Drive.

The dataset folder I used can be found here: [Dataset I used (Google Drive link)](https://drive.google.com/drive/folders/1dvPUVQG49epamQyqDUU34-RZqyRnmc4b)

# Steps for project:
1. Data collection and preprocessing
2. Face Detection using MTCNN
3. Face Recognition using VGGFace models
4. Face Recognition using FaceNet

## How to recompile the code (FRCodeWithVGG16.ipynb):
All of the code I wrote was run in a Google Colab notebook. To rerun the code, you would do the following:

1. You would need to change all of the filepaths to wherever those directories are stored on your machine or on Google Drive. 
In addition, you will notice that some filepaths contain **gdrive** instead of **drive**. This is because I ran out of Colab GPU on my main Google account, which is why I needed to continue writing code on a google colab notebook which was on a separate account than where my dataset was stored. 

2. Delete the train_new, valid_new, and test_new folders (these contained the faces after face detection). Then, uncomment the code in the section that says **Setup Stuff** to create those folders. After that, run that code along with the face detection to populate those folders with all of the faces.

3. Laslty, you can run the VGGFace and FaceNet code just as it is.


## Results: 
To see the results look at the end of the VGGFace section and the end of the FaceNet section.



