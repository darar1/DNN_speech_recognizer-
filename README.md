PROJECT LICENSE

This project was submitted by Dara Rouholiman as part of the NLP Nanodegree At Udacity.

As part of Udacity Honor code, your submissions must be your own work, hence submitting this project as yours will cause you to break the Udacity Honor Code and the suspension of your account.

Me, the author of the project, allow you to check the code as a reference, but if you submit it, it's your own responsibility if you get expelled.

Copyright (c) 2018 Dara Rouholiman

Besides the above notice, the following license applies and this license notice must be included in all works derived from this project.

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

# Natural Language Processing Nanodegree

# Voice User Interfaces

## Project: Speech Recognition with Neural Networks

## Author: Dara Rouholiman(dara.rouholiman@gmail.com)

### Install

TensorFlow with GPU support on your local machine Or Create a EC2 GPU instance on AWS/google cloud/floydhub

Switch Keras backend to TensorFlow.

### Code

Template code and required datasets were provided by Udacity in https://github.com/udacity.

## Project Overview

Building a deep neural network that functions as part of an end-to-end automatic speech recognition (ASR) pipeline! Your completed pipeline will accept raw audio as input and return a predicted transcription of the spoken language. 

STEP 1 is a pre-processing step that converts raw audio to one of two feature representations that are commonly used for ASR.
STEP 2 is an acoustic model which accepts audio features as input and returns a probability distribution over all potential transcriptions. After learning about the basic types of neural networks that are often used for acoustic modeling, you will engage in your own investigations, to design your own acoustic model!
STEP 3 in the pipeline takes the output from the acoustic model and returns a predicted transcription.
