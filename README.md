# Face-Mask-Detection
This was my first project, created during college as my Major Project 1. The project was extremely helpful during the COVID-19 pandemic, as it was designed to determine whether a person is wearing a face mask or not.

1.1- Inroduction 
In 2020, the largest pandemic in recent history spread across the world: COVID-19. As of May 1, 2021, there have been over 152 million cases and 3 million deaths worldwide. In many regions, these numbers are likely under-reported. Beyond the human toll, COVID-19 has had economic and social impacts due to distancing and protective measures. This project aims to create a mask detection system capable of recognizing whether people in surveillance-type video streams are correctly wearing their masks. This can be beneficial both during ongoing pandemics and in preparing for potential future ones.



1.2- Overview
Due to the real-time and practical deployment constraints of this task, we approached the problem with a focus on both performance and efficiency. The primary pipeline for accuracy uses a pre-trained face detector to extract faces from the frame, then passes the cropped faces to an image classifier. This mask-wearing classifier is trained on a large-scale synthetic dataset of 180,000 images divided into three classes: mask correctly worn, mask incorrectly worn, and no mask worn. We experimented with various models for this classifier, from traditional machine learning approaches such as random forest and Haar cascades to advanced computer vision architectures like DenseNet and ResNet.


**-:Chapter 2:-**
2.1. Related Works
Projects with similar objectives became quite popular during the pandemic. One method proposed using Haar-cascade-based feature detectors to identify the presence of the nose and mouth in a detected face. The logic is as follows: no mask is worn if a mouth is detected, the mask is worn incorrectly if a nose is detected but not a mouth, and the mask is worn correctly if neither the nose nor the mouth is detected. Although this approach is efficient and intuitive, it has limitations: it only works for fully frontal faces and can be easily fooled if a person covers their mouth and nose with their hand.

**-:Chapter 3:-**
3.1 Hardware Requirements
● Working WebCam
● 4 GB RAM and above
● 1TB Hard disk
● 32-bit processor or more
● I3 processor or more
● Operating System

3.2 Software Requirements
● Python
● OpenCV
● TensorFlow
● Keras
● Imutils
