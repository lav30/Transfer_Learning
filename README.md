<h1 align="center">Classification using Transfer Learning</h1>
<p>
</p>

![Alt text](Files/Banner.png?raw=true "Title")

![Alt text](TL.png?raw=true "Title")

## Table of Contents

- [Portfolio Link](#portfolio-link)
- [Project Title](#project-title)
- [Project Description](#project-description)
- [Project Poster](#project-poster)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Dataset Information](#dataset-information)
- [License](#license)

## Portfolio Link

[Portfolio](https://lav30.github.io/Transfer_Learning_for_Gas_Sensor_Data/) that elaborates the methodologies used in this project to optimize the chosen metrics for classification. 


## Project Description 

An important assumption in machine learning frameworks and algorithms is that the training and test sets must have similar label distributions and that a dataset must have thousands of observations to produce a good model. Oftentimes, real-world datasets have dissimilar label distributions and few observations to generate an effective model performance. In such cases, model performance can be improved, if the knowledge acquired through a network trained on a large dataset can be transferred successfully to smaller datasets. This project focuses on the proof of concept of transfer learning between gas sensor datasets. The experimental results indicate significant improvements in model test accuracy and other performance metrics upon applying transfer learning.

![GitHub last commit](https://img.shields.io/github/last-commit/lav30/Transfer-Learning-for-Gas-Sensor-Data)
![GitHub All Releases](https://img.shields.io/github/downloads/lav30/Transfer-Learning-for-Gas-Sensor-Data/total)

## Project Poster

![Alt text](Files/Lavanya_Ramesh_Naik.png?raw=true "Poster")

## Installation
[(Back to top)](#table-of-contents)

1. Install [Anaconda](https://www.anaconda.com) and all necessary libraries ( pandas, scikit-learn, matplotlib, numpy, etc) 
2. Install [Tensorflow](https://www.tensorflow.org/install/pip)

## Dataset Information 
[(Back to top)](#table-of-contents)

Three chemical gas sensor datasets have been used in this project to build models utilised for transfer learning. A large dataset with millions of observations serves as the source dataset and two, much smaller datasets serve as the target datasets. The aim is to use pre-trained networks as initializations for datasets with fewer observations.

1. [Source Dataset](https://archive.ics.uci.edu/ml/datasets/Gas+sensor+array+temperature+modulation)
2. [Target Dataset 1](https://archive.ics.uci.edu/ml/datasets/gas+sensor+array+under+dynamic+gas+mixtures)
3. [Target Dataset 2](https://archive.ics.uci.edu/ml/datasets/Gas+sensor+array+exposed+to+turbulent+gas+mixtures)

## License
[(Back to top)](#table-of-contents)

GNU General Public License, version 3 (GPLv3)
