# Chemical Gas Classification using Transfer Learning 

![Alt text](TL.png?raw=true "Title")

## Table of Contents

- [Project Title](#project-title)
- [Project Description](#project-description)
- [Project Poster](#projectposter)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Dataset Information](#datasetinformation)
- [License](#license)

## Project Description 

This project focuses on the proof of concept of transfer learning between several time-series gas sensor datasets. The experimental results indicate significant improvements in model test accuracy and other performance metrics upon applying transfer learning as opposed to traditional deep learning algorithms.

![GitHub last commit](https://img.shields.io/github/last-commit/lav30/Transfer-Learning-for-Gas-Sensor-Data)
![GitHub All Releases](https://img.shields.io/github/downloads/lav30/Transfer-Learning-for-Gas-Sensor-Data/total)

## Project Poster

[Here](<a href="lav30.github.io/Files/poster.pdf" target="_blank">PDF.</a> is the project poster presented at the Fall 2020 Symposium.

## Installation
[(Back to top)](#table-of-contents)

1. Install [Anaconda](https://www.anaconda.com) and all necessary libraries ( pandas, scikit-learn, matplotlib, numpy, etc) 
2. Install [Tensorflow](https://www.tensorflow.org/install/pip)

## Dataset Information 

Three chemical gas sensor datasets have been used in this project to build models utilised for transfer learning. A large dataset with millions of observations serves as the source dataset and two, much smaller datasets serve as the target datasets. The aim is to use pre-trained networks as initializations for datasets with fewer observations.

1. [Source Dataset](https://archive.ics.uci.edu/ml/datasets/Gas+sensor+array+temperature+modulation)
2. [Target Dataset 1](https://archive.ics.uci.edu/ml/datasets/gas+sensor+array+under+dynamic+gas+mixtures)
3. [Target Dataset 2](https://archive.ics.uci.edu/ml/datasets/Gas+sensor+array+exposed+to+turbulent+gas+mixtures)

## License

GNU General Public License, version 3 (GPLv3)
