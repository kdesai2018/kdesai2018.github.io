---
layout: post
title: current tasks
---

## lab

I just hopped off a call with my supervising PhD student. We discussed the current workflow in the lab with everyone working remote, and then jumped right into my tasks for the next few weeks.

1. Learn how to use Mechanical Turk with A/V recording. This is intended to substitute human trials, and will allow us to analyze the data to gauge intention. Ideally, this will allow us to finish up our current paper and submit it by mid-summer.

2. Fine-tune an object recognition model for shape recognition. Here’s where things get interesting. I’ve been playing around with deep learning for object recognition over the past year (on and off). Last summer, I ported [FAIR’s Detectron algorithm to a ROS-based platform](https://github.com/kdesai2018/ros-object-recognition), allowing for real time object detection on the robots. This project helped me get my feet wet with ROS and advanced object recognition algorithms.

Now, my task is to fine-tune a pre-trained model to recognize new shapes. I started by watching [this video](https://www.youtube.com/watch?v=aircAruvnKk) by 3Blue1Brown to remind myself of the theory behind Neural Nets. Next, my surfing led me to the [GluonCV toolkit](http://gluon-cv.mxnet.io/), which also published a whole bunch of tutorials about object recognition. [This](https://gluon-cv.mxnet.io/build/examples_detection/finetune_detection.html) tutorial got me started on the syntax for fine-tuning.

The goal for this task is to collect a novel dataset of shapes from the video and fine-tune a model using this data. Naturally, this runs the risk of overfitting the model on our dataset, since every video in the test set is similar to the train set. However, for this small dataset, we believe that the model will still perform to an acceptable margin of error.

## personal

I (re) started Infinite Jest by David Foster Wallace. I also read a really interesting [article](https://medium.com/@the_jennitaur/how-to-do-nothing-57e100f59bbb) on Medium about the benefits of nothingness, which is a timely read.
