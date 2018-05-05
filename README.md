# Distracted-Driver
This project involved using Convolutiontional Neural Networks to classify a dataset of images provided by the Kaggle State Farm Safe Driver
Competition.

The provided jupyter notebook displays importing the data, scalling, converting it to greyscale. After accomplishing this, I then
ran a series of CNNs to determine which would yield me the best accuracy without overfitting. 

The three different model included:
1) A sequential CNN that converted the data to a Dense Network.
2) A model that resembled a inception module that involved individual towers as convolutional stages. The output
was flattened into a prediction array.
3) This model used the previous model but added the element of BatchNormalization to prevent exploding gradients
which would cause overfitting.

Finally, the results were fairly good for my first go at Neural Networks. The accuracies were very high for 
the training and validation sets. With accuracies to the mid to upper 90s and average loss being around
0.10.
