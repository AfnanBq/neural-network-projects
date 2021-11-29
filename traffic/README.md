# Traffic
This project is implemented to classify the raod signs by using [German Traffic Sign Recognition Benchmark](https://benchmark.ini.rub.de/?section=gtsrb&subsection=news)(GTSRB) dataset.

## Table of contents
* [Introduction](#introduction)
* [Results](#results)
* [Technologies](#technologies)
* [Setup](#setup)
* [Contact](#contact)
* [Sources](#sources)

## Introduction
In this project I implemented neural netwrok from scratch by using TensorFlow to classify 43 types of raod signs. The implemented neural network consists 5 Conv layers, 4 Maxpooling layers, and a hidden layers that has 128 neurons. The following digram shows the summary information of the implemented neural network. 


## Results
Testing loss and accuracy:
- Adam 
* loss: 0.0569 
* accuracy: 0.9850

- SGD
*  loss: 0.1988
*  accuracy: 0.9450 

## Technologies
Project is created with:
* Python 3.6.8
* tensorflow 2.5.0
* scikit-learn 0.19.1
* numpy 1.19.5
* opencv-python 4.5.1.48
* 
## Setup
To run this project, install it locally:
* git clone https://github.com/AfnanBq/neural-network-projects.git
* cd /neural-network-projects/traffic
* install all the required libraries [Technologies](#technologies)
* * run the following command.
```
 python traffic.py gtsrb
```
## Contact
[Afnan Qalas](http://linkedin.com/in/afnanbalghaith)

## Sources
This project is inspired by [traffic](https://cs50.harvard.edu/ai/2020/projects/5/traffic/)
