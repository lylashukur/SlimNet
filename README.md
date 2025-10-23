# SlimNet
Computer vision project that I worked on with two other awesome student developers!

## Project Overview
SlimNet was built to reduce model size and inference time while maintaining strong accuracy on image classification tasks.
We compared:

- A baseline **Convolutional Neural Network (CNN)**
- A **Post-Training Quantized (PTQ)** version
- A **Quantization-Aware Training (QAT)** version

We visualized performance through heatmaps and confusion matrices to analyze where quantization improved or degraded predictions

## Instructions for running the SlimNet

Run the first 19 cells individually

This will install all the necessary dependencies for the original CNN and the PTQ model.
Once you are at the 20th cell, delete the runtime.

Deleting the runtime is at the top of the notebook where it says Runtime → Disconnect and delete runtime
Then install the required libraries (cells 21 and 22).

After the reinstallation, restart the session by going to the top and pressing Runtime → Restart session.

It is important to restart after installing so the new environment includes those libraries properly.
Run cells 23 and onward to run the QAT model, the testing, heatmap, and the confusion matrix.
