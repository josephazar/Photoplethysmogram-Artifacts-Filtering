# Photoplethysmogram-Artifacts-Filtering
This repository contains machine-learning solutions for Photoplethysmogram Artifacts Filtering. It is also the companion repository for our paper titled [Deep recurrent neural network-based autoencoder for photoplethysmogram artifacts filtering](https://www.sciencedirect.com/science/article/abs/pii/S0045790621000793) published in [Computers & Electrical Engineering](https://www.sciencedirect.com/journal/computers-and-electrical-engineering).


## Training
The computations were performed on an NVIDIA Tesla Titan X GPU. The evaluation and testing were done using Google Colab. The weights of the model were saved on my Drive. 
Make sure to change the path of the weights in the notebooks. 

## Data
The PPG dataset was collected using Shimmer3 GSR+Unit with a sampling frequency of Fs = 52 Hz in the Femto-ST laboratory department DISC, Belfort, France.
Some of the collected data samples are in the ppg.zip folder. Make sure you change the path to the data in the notebooks. 
The data in this repository have not been properly labeled by a specialist in physiological signals; hence, certain PPG windows may be incorrectly labeled.
The models in the notebooks are trained for a brief period for demonstration purposes; hence, there may be variations between the notebook and paper outcomes.

