# Air-Canvas-Drawing-in-the-air-using-AI
<p align="center"> 
  <img src="Template/handgesture detection.gif" alt="img Logo" >
</p>
<h1 align="center"> Air-Canvas-Drawing-In-Air-Using-AI </h1> 

</br>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- ABOUT THE PROJECT -->
<h2 id="about-the-project"> :pencil: About The Project</h2>

<p align="justify"> 
 The aim of the project is to develop an AI-based system that combines hand gesture detection, machine learning algorithms, Python programming, and OpenCV to create a natural user interface for digital art. The project focuses on developing a system for hand motion recognition to enable digital writing and drawing. By utilizing advanced methods such as Python and OpenCV, the project aims to create a seamless and intuitive experience for users to interact with digital art using hand gestures. The system will enable users to perform gestures that correspond to specific actions, such as drawing, erasing, selecting colors, and navigating through the digital canvas. The goal is to bridge the gap between traditional art tools and digital art technology, providing users with a new and innovative way to express their creativity in the digital realm.
</p>
<!-- PRE-PROCESSED DATA -->
<h2 id="Problem-statement"> :diamond_shape_with_a_dot_inside: Problem Statement</h2>

<p align="justify"> 

* Develop a system that allows users to draw on a virtual canvas using hand gestures instead of physical tools or touch-based interfaces.

* The system should accurately track hand movements, recognize specific gestures, and translate them into actions on the canvas.

* The goal is to rely on computer vision and machine learning technology to develop a responsive and user-friendly drawing experience that replicates actual drawing.

</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- PREREQUISITES -->
<h2 id="prerequisites"> :fork_and_knife: Prerequisites</h2>

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) <br>
[![Made withJupyter](https://img.shields.io/badge/Made%20for-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try) <br>
[![made-with-VSCode](https://img.shields.io/badge/Made%20with-VSCode-1f425f.svg)](https://code.visualstudio.com/) <br>

<!--This project is written in Python programming language. <br>-->
The following open source packages are used in this project:
* OpenCV
* Pandas
* NumPy
* TensorFlow
* Keras
* Matplotlib
* Sklearn
* pathlib
* Mediapipe
* PyTorch



![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- :paw_prints:-->
<!-- FOLDER STRUCTURE -->
<h2 id="folder-structure"> :cactus: Folder Structure</h2>

    Air-Canvas-Drawing-In-Air-Capston
    .
    ├── Models
    │   ├── MNIST .ipynb
    │   └── ASL.ipynb
    │   └── Final
    ├── Dataset 
    │   └── MNIST
    │   └── subsample
    ├── README
  
   
<!-- DATASET -->
<h2 id="dataset"> :floppy_disk: Dataset</h2>
<p> 
  
 <h2> MNIST Dataset</h2>

* The dataset is well-structured and easy to understand and work with.
* The dataset consists of grayscale images with a fixed size of (48, 48).
* The dataset was divided into training, testing, and validation sets.
* The training set contains 50,000 images, the testing set has 10,000 images, and the validation set has 10,000 images.
* The dataset allows for faster model training and iteration due to its relatively small size.
* MNIST dataset is widely used for quick prototyping and experimenting with different models and architectures.
* The dataset's handwritten digits are visually interpretable, enabling insights into model performance and representations.
* Achieving high accuracy on MNIST does not guarantee similar performance on more complex real-world datasets.
<br>

<p> <h2> Hand Gesture Detection</h2>

Here i'm using a hand gesture detection.for this project does not require a separate dataset.
* The dataset consists of images capturing various hand gestures performed by individuals.
* Each image or video frame is labeled with the corresponding gesture class to facilitate supervised learning.
* The dataset covers a diverse range of gestures, including basic gestures such as Call, dislike, fist, four, like, mute, okay, one, palm, peace, peace inverted, rock, stop, stop_inverted, three, three2, two_up, two_up_inverted.
* The gesture classes are taken from American Sign Language (ASL), a universal language for communicating with Deaf people.
* The dataset aims to bridge the communication gap by converting hand gestures to text in real-time.
* The dataset includes a variety of hand shapes, sizes, and orientations to account for the natural variability in human hand appearances and postures.

<br>
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- ROADMAP -->
<h2 id="roadmap"> :dart: Roadmap</h2>

<p align="justify"> 
  Initially We had two models: one using VGG with ImageNet for facial recognition and another using CNN for audio recognition. There was a flask app that was genrating emotions by uploading the video onto a webpage.<br>
  The goals of this project include the following:
<br><br>
1. After evaluating the drawing air model using the MNIST dataset and testing on VGG19, we found the accuracy to be very satisfactory. Subsequently, we further improved the accuracy by adding six more layers to the model.<br>
2. Develop a drawing recognition model on MNIST and a hand gesture detection model on the custom dataset, then integrate them to create a real-time system for detecting hand gestures and recognizing drawing actions.<br>
3. Implement real-time visual feedback for users as they interact with the air canvas system. This could include displaying the drawing trail, cursor, or gesture recognition results.<br>
4. To overcome hardware issues encountered while using MediaPipe, we adopted a traceback method, resulting in a significant improvement in the output. Previously, the drawing appeared as a dotted line due to interruptions caused by hardware limitations. <br>
5. With the traceback approach, we have successfully achieved a continuous line image, providing users with a smoother and more seamless drawing experience. This enhancement ensures that hand gestures are accurately tracked and translated into fluid strokes on the virtual canvas, enhancing the overall user interaction and creativity in the air canvas system.<br>







