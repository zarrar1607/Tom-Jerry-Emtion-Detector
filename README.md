# AIM
Create machine learning model capbale of identifying 4 emotion : angry, sad, surprised, happy, and unknown. I did this using Tensorflow Object Detection API. There are other ways available like dot-based feature extraction, etc but I found this way more effective. This is also a Deep learning challenge given by HackerEarth. For more information check the following point.

# [HackerEarth Deep Learning Challenge](https://www.hackerearth.com/challenges/competitive/hackerearth-deep-learning-challenge-emotion-detection-tom-jerry-cartoon/)
### Problem statement
There is no one around the world who doesn’t know of the animated comedy series, Tom and Jerry. Let’s admit it—all of us still love the iconic show and wish to catch a glimpse of Tom’s and Jerry’s constant notorious banter. Jerry leaves no stone unturned to annoy Tom—be it getting Tom in trouble with his landlady Mammy Two Shoes and his arch-nemesis Spike, making a fool out of him in front of his love interest Toodles Galore, or beating him for bothering Nibbles or Quaker. No matter what, we always end up laughing till our stomachs hurt.

On the International Day of Happiness, we are bringing back all the joy and happiness with this challenge. In this challenge, you are required to build a model that detects emotions of the characters in a video frame from our most-loved show, Tom and Jerry. 
Your task is to extract frames from a video clip provided and classify the primary character’s emotion into one of the five classes: angry, happy, sad, surprised, or Unknown.

### Dataset
The dataset consists of two parameters—‘Frame_ID’ that indicates the frame of the video and ‘Emotion’ that categorizes the emotion of the primary character into different labels: angry, happy, sad, surprised, or Unknown.
The benefits of practicing this problem by using Machine Learning/Deep Learning techniques are as follows:
- This challenge will encourage you to apply your Machine Learning skills to build models that analyze and classify frames of videos</li>
- This challenge will help you enhance your knowledge of multi-label image classification actively. It is one of the basic building blocks of Deep Learning</li>

The challenge is to build a model that detects the emotions of Tom or Jerry in each video frame.

# Soliving Steps
1. Download [Tensorflow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection) and flow each step, i.e., go through it's [README.md](https://github.com/tensorflow/models/blob/master/README.md) and download all prerequisite.</li>
2. Merge the files of this github repository with models/research/object_detection folder on your computer.</li> 
3. Make the neccessary file path changes
4. Run Train.py file inorder to train your custom model using the exsisting inference model in this repo
5. Execute object_detection.ipynb 
