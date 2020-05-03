# Archaeology and Machine Learning

## The Project
Main Goal of the Project is tocreate Machine Learning Model which will be able to identify ancient burial places on drone photos.

## The Data
My data contains 550 photos made by me in June of 2018 in Mongolia, Bulgan Province.  
The photos were made with a DJI Phantom Pro drone. Usually I prefer to make photos after careflly planning a flight path and use a grid system with a constant elevation, but this time I didn't have any previous information about the whereabouts of the place.
The photos were 
The original photos had dimensions of 4000 x 3000, with 72 x 72 DPI.
Most of the circles had very clean edges and were perfectly visible on the photos, while nearly 30% of them had very low visibility (probably these burials were older).

## The Workflow
In order to have larger amount of data and also to reduce the dimensions of photos as the first step I have sliced each photo to 20 equal slices.
This way I have obtained 11 000 photos with dimensions of 800 x 750.
As the second step I had to label 70% of the images.

## The Model
I have trained number of Convolutinal Neutral Networks with different number of hidden layers, pooling number, optimizers and activation functions. I have tried differnt data kinds of data augmentation and dropout regularisation.

## Result
My baseline had 55% accuracy, and my best model could reach 93% accuracy.

## Future Plans
I would like to be able to count the number of burials (at least with 80% accuracy), measure them try to use this model on high resolution Satelite Pictures.

## Further information about self-acquired data
https://medium.com/@mina_77131/an-example-of-archaeological-drone-surveying-b7e2a13f657
