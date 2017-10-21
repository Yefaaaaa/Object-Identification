# Object-Identification
Python framework -- OpenCV, Tensorflow

Tensorflow modificaition will coming soon

# Data Preparation:
1. Where these data come from?

Thanks to the Professor Fei-Fei Li, who is teaching computer vision in Stanford. She hosts the ImageNet which is a big free image database for research to download the label images. ImageNet is an image dataset organized according to the WordNet hierarchy. Each meaningful concept in WordNet, possibly described by multiple words or word phrases, is called a "synonym set" or "synset". There are more than 100,000 synsets in WordNet, majority of them are nouns (80,000+). In ImageNet, we aim to provide on average 1000 images to illustrate each synset. Images of each concept are quality-controlled and human-annotated. In its completion, we hope ImageNet will offer tens of millions of cleanly sorted images for most of the concepts in the WordNet hierarchy.

2. Download the data

There are thousands of images existing in the ImageNet. It is not easy to download and label all image by manually. Thus, I write the python program to download the images. 

Download the images will cost you a long time. After I downloaded the image, I figure out there are not images are useful because some of the links are expired but the ImageNet didnot update the link. Thus, I write another python script to clean the useless image.

The images are ready to use but it doesnot fit the OpenCV module usage, so, I need to translate images to the certain format. I will use the OpenCV on Linux to train the image information to the .xml file. In my case, the equipment is limited. If I train the huge image set, the machine may run for one or two days. Normally, researchers upload the images to the online platform and then remote train the image.

I need to write one more function to collect all the images information for training. 

3.<b>Tanning</b>

Move all the images and the .txt file to Linux platform. In this step, I used the OpenCV build-in function to train the data. It doesnot require too much coding skills but you need to know how to run the Linux command. At the end, it will generate the .xml file for the image you trained. I can apply the Python OpenCV module to this the .xml file. 


# Copy Right
Everytime when you ues this code, you need to include the author name. It is a open source for everyone. 

# Author
Yefa Mai

