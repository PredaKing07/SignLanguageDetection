# LinguaVision: Sign Language to Text

A real-time system that turns **hand gestures into readable text**. Webcam frames are processed with OpenCV and classified by a convolutional neural network (CNN).

**Team project.** This was a 4-member major project in image processing at college. The code lives in the team repository:
👉 **[Ayush-1127/Sign-Language-to-text-converter](https://github.com/Ayush-1127/Sign-Language-to-text-converter)**

## Pipeline
Frame capture → preprocessing (gradient image) → CNN classification → live text output

## My contribution
I worked on the **image preprocessing stage**: converting raw hand images into **gradient images**, where the hand's shape and edges stand out as gradients, so the CNN gets a cleaner and more consistent input to classify.

## Tech stack
Python · OpenCV · PyTorch (CNN) · image processing
