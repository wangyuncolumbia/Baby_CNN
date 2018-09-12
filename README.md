# Baby_CNN

# Version 0  EchoBaby 2D Unet Experiment

(1)  Training data 

We used 24 subjects’ good T2 segmentations (WM, GM, and CSF). 
Notce: There is no preprocessing of this step. But we will do that later. 

Threshold The probability mask at four different levels: 0.5,0.6,0.7,0.8 
Bigger than threshold, will be 1, smaller than threshold, will be 0. 

We will have binary mask for each type of tissue. 

(2)  Test using Gray Matter mask first using Unet. 

