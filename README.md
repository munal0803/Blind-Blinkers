# Blind-Blinkers
A python Software which acts as guide eye for blind person
# Inspiration
When I saw specially-abled people struggling to get simple things done due to vision impairment, I felt really sad. I want to help these people through this program so that they can figure out where their items are and where they are kept.

# What it does
Consider a scenario. A blind person is alone at home and needs something like he wants to find his movable chair but has forgotten where it was placed. Normally he would have to guess the direction and try by reaching out to the distances if there is no one to help. In this case, he would have to waste a lot of energy and time and there is also a risk of them hurting or wounding themselves in the process. Our project solves this problem.

A person using this would simply open this project, it would ask him what he wants and he would simply say "chair", the project would detect and start searching for the chair with the help of machine learning item detection using the camera of the device. The person then would have to simply rotate and would try to find the chair using his phone. As soon as the software detects a chair, it calls out just like a metal detector beeps. Following this sound, the person can find the object he wants (in this case a chair) and reach to it with ease.

Thus, this software acts like a guide dog helping out a blind person

# How we built it
We use Opencv and Single Shot Detector (SSD) algorithm for object detection. SSD is a method for detecting objects in images using a single deep neural network. Along with this, we use pyttsx3 for Text-To-Speech conversion and Speech Recognition for converting users' voices into text.

# Challenges we ran into
We wanted to solve a problem for blind people but were confused about how could we do it.
After coming up with this idea voice recognition and speaker acted as a small problem but was resolved.
Training a model for detecting posed a problem.
After this, coming up with a way of transferring and connecting a phone to the software
Accomplishments that we're proud of
Through this project, we aim to create a level playing field and help our specially-abled friends to locate and identify things easily. We are proud of the fact that the 
