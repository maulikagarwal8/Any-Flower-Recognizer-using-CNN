# Any-Flower-Recognizer-using-CNN
An ml model leveraging benefits of CNN to recognize any image of flower uploaded by user

It uses Flowers-102 datasets images to train itself

## Steps involved in making are:
1->Downloading the data and visualizing it (8189 images of 102 flower species):.\
   data: https://www.robots.ox.ac.uk/~vgg/data/flowers/102/102flowers.tgz. \
   labels: https://www.robots.ox.ac.uk/~vgg/data/flowers/102/imagelabels.mat. \
2->Writing hyperparameters, device.\
3->Writing dataset class, defining dataset and dataloader.\
4->Visualizing the data after dataset transformation.\
5->Writing the model (+ testing).\
6->Writing model, optimizer, loss function.\
7->Adding Check accuracy function and implementing to the training.\
8->Writing the training loop and training the model.\
9->Visualizing model predictions.


### Test Results
After training and testing Accuracy of :\
->55% was achieved with my custom model.\
->78% was achieved using ResNet model.

## What its look like
