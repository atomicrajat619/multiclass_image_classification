# multiclass_image_classification
### Multi-class Flower classification project done as a part of DL guided projects under TMLC(The Machine Learning Company)

## Dataset 
The dataset consist of 104 class of flower images divided into train, valid and test data folders.

## Model
There are two models used for this project 
1. Transfer Learning by using VGG16 as base model and adding some layers at the end leaving the weights of imagenet.

2. Custom CNN architeture trained from scratch.

## Outcome

custom model performed well than the transfer learning but it was hard to generalize as the training accuracy was high than the validation accuracy.

some tuning and chnage in the  architecture may result in better outcome.
there is a scope of improvement in this project.

## Challenges 

since dataset consist of many number of classes i.e 104 the model is finding it hard to classify all flowers correctly since there is more correlaion between different flowers in terms of features. 
