# Project Title: "SignVision: Bridging Communication Gaps with ASL Recognition"

## Introduction:
In a world where communication is fundamental, American Sign Language (ASL) empowers millions in the deaf and hard of hearing community. However, barriers persist. "SignVision," led by Philipp Langfeldt and Joana Hoang, seeks to break these barriers using machine learning and computer vision for real-time ASL recognition.

## The Challenge:
Recognizing the complexity of ASL, we face challenges like varied signing speeds, lighting conditions, and background noise. Our goal is precise recognition.

## The Roadmap:
We'll lay foundations in ML, deep learning, and Python. We collect a vast ASL dataset from YouTube, employing innovative algorithms for data extraction. The data undergoes thorough labeling and preprocessing. We're developing deep learning models and fine-tuning them for accuracy.

Our "SignVision" envisions a world where ASL users can communicate effortlessly. Our project aims to create inclusive solutions, such as real-time translation apps. By breaking communication barriers, "SignVision" empowers the deaf and hard of hearing community, fostering inclusivity and understanding. 

Together, we're paving the way for a more inclusive future.

_

### Day 1-2: Setup, Learn the Basics, ASL Background

Install TensorFlow and any necessary libraries on the machine.
Spend the first two days learning the fundamentals of machine learning, deep learning, and computer vision.
Research and understand the basics of American Sign Language. Familiarize with the challenges of ASL recognition, such as variations in sign shapes, lighting conditions, and background noise.

### Day 3-4: ASL TensorFlow and Object Detection

Learn the basics of TensorFlow, a popular deep learning framework. Explore object detection using TensorFlow's Object Detection API. 

### Day 5-6: Dataset Collection and Preprocessing

Collect an ASL dataset / create a own by recording ASL gestures.

Addtional using the dataset of WLASL (World Level American Sign Language) Video. Explore ways to collect ASL data from YouTube. Consider using YouTube APIs or third-party tools that can download videos. Create a list of YouTube channels or videos that contain ASL sign language content. Develop a script or program to download these videos automatically. Consider using Optical Character Recognition (OCR) techniques to extract ASL signs' labels or descriptions from video titles, descriptions, or subtitles to aid in data labeling. 

Preprocess the data, including resizing, normalization, and data augmentation to improve model performance.
Split the data into training, validation, and test sets.

### Day 7-8: Model Training and Evaluation

Train a deep learning model for real-time ASL sign language recognition using TensorFlow and the Object Detection API.
Experiment with different architectures, hyperparameters, and loss functions.
Evaluate the model's performance using appropriate metrics like accuracy, precision, recall, and F1-score.
Tune the model to improve its performance.
Implement real-time webcam or video input for live ASL recognition.


### Day 9-10: Algorithm Development

Research and experiment with algorithms for automatically detecting and extracting ASL signs or gestures from video frames.
Implement an algorithm to identify and extract the ASL signs from the video frames.
Organize the extracted images into folders based on the sign they represent.

# Goal: 
Deploy a model for real-time recognition, whether it's in a web application, a mobile app, or on a dedicated hardware device.

Link: WLASL dataset - https://www.kaggle.com/datasets/risangbaskoro/wlasl-processed/
