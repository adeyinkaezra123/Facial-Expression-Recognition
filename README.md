# Facial-Expression-Recognition
Facial-Expression-Recognition in Python and TensorFlow. Detects faces in video and recognize the expression(emotion)

#  Dependencies

FER requires:

Python (>= 3.3)

TensorFlow (>= 1.1.0) 

OpenCV (python3-version) 

Only tested in Ubuntu and macOS Sierra. I'm not sure if this would work well on other platfotms. If you encounter any problem, open an issue, I'll do my best to solve that.

#  Usage
#     demo
To run the demo, just type:

# python3 main.py
Then the program will create a window to display the scene to be capture by the webcamera. You'll need to press SPACE key to capture face in current frame and recognize the facial expression.

If you just want to run this demo instead of training the model from scratch, the following content can be skipped.
train models
If you want to train a model from scaratch by yourself, download the fer2013 datasets in kaggle(91.97MB). Then extract the data to data/fer2013 folder.

It's is import that modifying the MODE(in main.py) from demo to train before you start training. Then type:

# python3 main.py
