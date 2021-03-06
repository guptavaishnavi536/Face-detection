# Face-detection
This repository consists of a basic approach towards face detection using Viola Jones algorithm.
Viola Jones algorithm is named after two computer vision researchers who proposed the method in 2001, Paul Viola and Michael Jones in their paper, “Rapid Object Detection using a Boosted Cascade of Simple Features”. Despite being an outdated framework, Viola-Jones is quite powerful, and its application has proven to be exceptionally notable in real-time face detection. This algorithm is painfully slow to train but can detect faces in real-time with impressive speed.

Given an image(this algorithm works on grayscale image), the algorithm looks at many smaller subregions and tries to find a face by looking for specific features in each subregion. It needs to check many different positions and scales because an image can contain many faces of various sizes. Viola and Jones used Haar-like features to detect faces in this algorithm.

The Viola Jones algorithm has four main steps, which we shall discuss in the sections to follow:

-> Selecting Haar-like features,
-> Creating an integral image,
-> Running AdaBoost training,
-> Creating classifier cascades

There are 3 types of Haar-like features that Viola and Jones identified in their research:

-> Edge features
-> Line-features
-> Four-sided features

To read about it in detail refer to the link below:
https://www.mygreatlearning.com/blog/viola-jones-algorithm/
