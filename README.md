# Face-Recognition-and-Detection

OpenCV was designed for computational efficiency and with a strong focus on real-time applications. So, it’s perfect for real-time face recognition using a camera.

The 3 Phases
To create a complete project on Face Recognition, we must work on 3 very distinct phases:

Face Detection and Data Gathering
Train the Recognizer
Face Recognition

Installing OpenCV 3 Package
I am using a Raspberry Pi V3 updated to the last version of Raspbian (Stretch), so the best way to have OpenCV installed, is to follow the excellent tutorial developed by Adrian Rosebrock: Raspbian Stretch: Install OpenCV 3 + Python on your Raspberry Pi.

I tried several different guides to install OpenCV on my Pi. Adrian’s tutorial is the best. I advise you to do the same, following his guideline step-by-step.

Once you finished Adrian’s tutorial, you should have an OpenCV virtual environment ready to run our experiments on your Pi.

Let’s go to our virtual environment and confirm that OpenCV 3 is correctly installed.

Adrian recommends run the command “source” each time you open up a new terminal to ensure your system variables have been set up correctly.

source ~/.profile
Next, let’s enter on our virtual environment:

workon cv
If you see the text (cv) preceding your prompt, then you are in the cv virtualenvironment:

(cv) pi@raspberry:~$
