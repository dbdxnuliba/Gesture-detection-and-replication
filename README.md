# Gesture-detection-and-replication
## Table of contents
* [About the Project](#about-the-project)
  * [Tech Stack](#tech-stack)
  * [File Structure](#file-structure)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
 * [Usage](#usage)
 * [Results and Demo](#results-and-demo)
* [Future Work](#future-work)
* [Troubleshooting](#troubleshooting)
* [Contributors](#contributors)
* [Acknowledgements and Resources](acknowledgements-and-resources)
 
## About the Project
To detect and recognise basic hand gestures and imitate them using a simulation of a robotic hand. Recognition of gestures can be done using various approaches like CNN (Convolutional Neural Network), feature engineering (such as binary thresholding, circle detection, etc.), and others. The simulation will be done using CoppeliaSim.In this project will be focusing on two methods. 1.CNN's(for more information see in project resources link below) 2.opencv(contours detection).

![image](https://user-images.githubusercontent.com/84779934/137261894-87074cd3-31a4-4884-a320-50d0a9f6aa65.png)

So as you can see in the image when **_vertical fist_** was detected then the arm that you see in right side window is oriented at some position.
similarly you can move the arm by detecting different gestures.

### Tech Stack:-
Technologies used for this project
* [Python](https://www.python.org/)
* [opencv](https://opencv.org/)
* [Numpy](https://numpy.org/doc/#)
* [Remote API python Coppeliasim](https://www.coppeliarobotics.com/helpFiles/en/remoteApiFunctionsPython.htm)
* [keras](https://keras.io/) (Optional)
* [Google colab](https://colab.research.google.com/)


### File Structure
    .
    ├── docs                    # Documentation files (alternatively `doc`)
    │   ├── report.pdf          # Project report
    │   └── results             # Folder containing screenshots, gifs, videos of results
    ├── code files                  # code of both approaches( 1.using pretrained cnn model 2. using contours)
    ├── coppeliasim scene and final code  # scene which you need to open and final merged code
    ├── some reference notes  # linear algebra and deep learning notes
    ├── README.md                 

## Getting started:-


### Prerequisites
Follow below steps
* Install coppeliasim:   [https://coppeliarobotics.com/downloads](https://coppeliarobotics.com/downloads)

* Any code editor

* Python  [Python 3.6 and above](https://www.python.org/downloads/release/python-360/)
* The installations provided below are installed using pip. so you first need to install pip.

     [Install pip following this steps](https://www.geeksforgeeks.org/how-to-install-pip-on-windows/)
* To install numpy
 ```sh
    pip install numpy
  ```
* To install OpenCV
  ```sh
   pip install opencv-python
  ```
* To install keras(required if you are using cnn approach)

  [steps to install keras](https://www.tutorialspoint.com/keras/keras_installation.htm)
  
* If you want you can install matplotlib,cvzone and other libraries.
### Installation
1. Clone the repo
```sh
git clone https://github.com/Dhruv454000/Gesture-detection-and-replication
```
## Usage

(steps to run project)

After cloning the repo transfer the files to your project folder. Open terminal and go to the project folder and run the following commands:-

1.First open coppeliasim and then open the scene in coppeliasim.

2.Now run **_python filename.py_** in cmd (make sure you are in same directory where your filename.py is saved)

## Results and Demo

* [VIDEO OF PROJECT](https://drive.google.com/file/d/1MYeF46O8lwtb_kGuzHJm7bSkJHGjh_S8/view?usp=sharing)

## Future work
* To update the project with new approaches and add more gestures            
* To do more research on CNN approach.

## Troubleshooting

* Common errors while configuring the project

## Contributors
* [Dhruv Kunjadiya](https://github.com/Dhruv454000)
* [Gaurav Kumar](https://github.com/GauravKumar9920)

## Acknowledgements and Resources
* [SRA VJTI](https://www.sravjti.in/) Eklavya 2020


 * Some project resources and links:-
   * [Deep learning specialization](https://www.coursera.org/specializations/deep-learning)
   * [linear algebra](https://www.youtube.com/playlist?list=PL0-GT3co4r2y2YErbmuJw2L5tW4Ew2O5B)
   * [Hand gesture model using CNN's](https://towardsdatascience.com/tutorial-using-deep-learning-and-cnns-to-make-a-hand-gesture-recognition-model-371770b63a51)
   * [contours approach](https://www.youtube.com/watch?v=v-XcmsYlzjA)
   
     [refer this doc for more clearity for contours approach](https://docs.google.com/document/d/10_vhaOWwhwUkZT0DO1SDguEUwxTreZwWuqfsgjbF5bI/edit#heading=h.3f6ncedfulu)
   * [Remote api functions coppeliasim](https://www.coppeliarobotics.com/helpFiles/en/remoteApiFunctionsPython.htm)
   * [To make  coppelia scene  follow this](https://www.coppeliarobotics.com/helpFiles/en/inverseKinematicsTutorial.htm)

  

