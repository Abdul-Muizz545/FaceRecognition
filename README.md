# FaceRecognition
This is a project where face recognition using CNNs is done for 30 actors in the IMDB-WIKI dataset (https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/). From this dataset, I only used the actors in IMDB and not in Wikipedia. 
All of the images used for these 30 actors were stored in the _train_, _valid_ and _test_ folders. Lots of images were grayscale and had to be removed since the CNN models only accepted colored images as input.

The dataset folders I used can be found here: **https://drive.google.com/drive/folders/1dvPUVQG49epamQyqDUU34-RZqyRnmc4b**

The steps for my project were as follows:
1. Data collection and preprocessing
2. Face Detection using MTCNN
3. Face Recognition using VGGFace
4. Face Recognition using FaceNet

