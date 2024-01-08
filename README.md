# MDR-TB-detection

MDR- TB Detection Using (Pytorch)

PyTorch is python native, and integrates easily with other python packages, which makes this a simple choice for researchers. 

Here, I am using Residual Network (ResNet) via transfer learning, a popular deep learning neural network model, to classify MDR TB chest X-ray scans. This dataset consists of around 5,000 and 600 images in the training and testing set respectively. It is quite small by today's big era standard, and it presents some challenges such as data imbalance that I will attempt to mitigate. By leveraging the power of transfer learning, we are able to 'transfer' the weights of low-level features (e.g., lines, shapes, etc) that were detected in a pretrained model. Doing so saves us the need to train a model from scrach, which can be challenging for those who do not have a 'big' enough dataset or computational resources.


The process is as follows:

Data Loading and Structure
Preparing Train, Validation & Test Data
Set Up GPU
Creating Model Class
Train and Evaluate Model
Accuracy and Loss Plots
Predicting on Test Set
Model Evaluation Metrics
Plot Predictions against Actual Labels
Conclusion
