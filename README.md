# Automated-Analysis-of-Videos-Towards-Compliance-Monitoring
In this report, we explore various techniques from machine learning, deep learning and computer vision in order to solve peculiar real-world problems in analysing diverse videos. We illustrate various state-of-art methodologies and pipelines using convolutional neural networks that can be commonly used to solve domain specific challenges in object detection and classification, scene classification, etc. We primarily focus on feature engineering, fine tuning, transfer learning, region based and single pass object detection models. For each of the mentioned techniques, we investigate in-depth their relevance from a theoretical as well as application perspective. Towards this end, we focus on the efficacy of customized deep learning models using data from the deployment scenarios and compare them with off-the-shelf models using generic data from the Internet. Finally, since most of these models are deployed on-site where resources are limited, it is imperative to have models which do not require GPUs. We exhibit customization of resource constrained models and deploy them on embedded devices without substantial loss in accuracy.

To demonstrate the effectiveness of these techniques we consider multiple compliances from a real-world classroom scenario and develop an understanding on the pros and cons of using these measures. 
The following challenges are considered:

1. Counting the number of students precisely
2. Classifying classroom scenarios into class started | not started at a frame level
3. Detecting if each student is wearing uniform
