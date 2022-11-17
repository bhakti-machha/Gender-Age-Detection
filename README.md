# Gender-Age-Detection

Gender and Age Detection Python Project- 
To build a gender and age detector that can approximately guess the gender and age of the person (face) in a picture using Deep Learning on the Adience dataset.

In this Python Project, we have used Deep Learning to accurately identify the gender and age of a person from a single image of a face.The predicted gender may be one of ‘Male’ and ‘Female’, and the predicted age may be one of the following ranges- (0 – 2), (4 – 6), (8 – 12), (15 – 20), (25 – 32), (38 – 43), (48 – 53), (60 – 100) (8 nodes in the final softmax layer). It is very difficult to accurately guess an exact age from a single image because of factors like makeup, lighting, obstructions, and facial expressions. And so, we make this a classification problem instead of making it one of regression.

The Dataset:

https://www.kaggle.com/datasets/ttungl/adience-benchmark-gender-and-age-classification

For this python project, we’ll have used the Adience dataset; the dataset is available in the public domain and you can find it here. This dataset serves as a benchmark for face photos and is inclusive of various real-world imaging conditions like noise, lighting, pose, and appearance. The images have been collected from Flickr albums and distributed under the Creative Commons (CC) license. It has a total of 26,580 photos of 2,284 subjects in eight age ranges (as mentioned above) and is about 1GB in size. The models we will use have been trained on this dataset.


You’ll need to install OpenCV (cv2) to be able to run this project. 

-->pip install opencv-python

Other packages you’ll be needing are math and argparse, but those come as part of the standard Python library.

<h1>Output</h1>

![WhatsApp Image 2022-11-04 at 4 12 36 PM](https://user-images.githubusercontent.com/88078110/202443899-f56d3d62-225a-4ea0-8038-217017259130.jpeg)
