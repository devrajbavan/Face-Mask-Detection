# Face-Mask-Detection
this my first project created in the college time as my Major Project 1. the project was too helpfull for covid times which was the was created to find weather a perrson is wearing a face mask or not...


1.1- Inroduction 
In 2020, the largest pandemic in recent history spread through the world: COVID-19. As
of May1st, 2021, there have already been 152 million cases and 3 million deaths around
the world . In many regions, those numbers are considerably under-counted . Beyond
that, many parts of the world have slowed or stopped due to the human, economic, and
social impacts of distancing and protection measures. For the purpose of the ongoing
pandemic and predictions for future pandemics, this projesct seeks to create a mask
detection system that is capable of recognizing whether people in surveillance-type
video streams are correctly wearing their masks.


1.2- Overview
Due to the real-time and real-world deployment constraints of such task, we decided to
tackle this problem from two fronts - performance and efficiency. The first pipeline that
focuses on accuracy uses a pre-trained face detector to extract faces from the frame, then
passes the cropped face stoan image classifier. This mask-wearing classifiers trained on a
large-scale synthetic dataset of 180,000 images divided into three classes: mask correctly
worn, mask incorrectly worn, and no mask worn. We experimented with various models
for this classifier, from traditional machine learning approaches such as random forest
and Haarcascades to state-of-the-art computer vision architectures
such as Dense Net and Resent.


**-:Chapter 2:-**
2.1. Related Works
Projects with similar intent have been quite popular due to the ongoing pandemic. A
method was proposed to utilize hear-cascade based feature detectors to individually
determine the presence of nose and mouth from a detected face .Their logic follows that
no mask is worn if we can successfully detect a mouth from the face, mask is worn
incorrectly if we can detect a nose by not a mouth, and mask is worn correctly if we can
detect neither a nose nor a mouth. This approach is efficient and intuitive but has severe
limitations - it can only process full-frontal faces and one can easily trick the detector by
covering their mouth and nose with their hand.


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
