# **CSE 676 Project**
Dog Breed Classification using Ensemble Pretrained Models
#### Team members: Bowen Liang, Zihan Wang, Guanchong Huang
Convolutional neural network (CNN) is a classical model in machine learning. Its expanded network and expanded function play an important role in image classification and recognition. In the research of CNN, due to the complexity of its parameters, it often requires a lot of time and energy to adjust the parameters to achieve better output results. In order to realize dog breed recognition, this project first built the CNN from scratch framework and adjusted the parameter structure. According to the performance of the experimental results, we used three pretrained models: VGG16, ResNET50 and InceptionV3, and in the practice stage of these three models, we have achieved good accuracy after adjusting the hyperparameters. In the last stage of the experiment, the team members fused the features of the three models used into an ensemble model and significantly improved the accuracy. Finally, we evaluated the accuracy, advantages and disadvantages of the above methods and proposed future improvement.
### Steps to run the code
+ Download dataset from [kaggle dog breed identification](https://www.kaggle.com/competitions/dog-breed-identification/data)
+ Put the ***train, test, and labels.csv*** into the folder.
+ Run the ***.ipynb file.***
