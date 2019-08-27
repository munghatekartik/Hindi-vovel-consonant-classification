# Hindi-vovel-consonant-classification

The goal is to identify the vowel and the consonant of each character image using Convolutional Neural Networks.
Each image is 64x64 pixels, and contains the character to be classified superimposed over a random scenic background. And will be presented with training set of 10,000 images each, for Hindi.
We have to classify the text into consonant and vowel. The firs thing therefore is to think about the final layer and the loss function.
The neural network needs to be designed such that at the output layer, we have two separate sets of 10 classes, one set for vowels and the other set for consonants with a softmax.
Once you arrive at the Loss value for Vowels and Consonants, you have to sum them to get a Combined Loss. You can then use the Combined Loss value for back-propagation. 

The Vovel Accuracy was found to be 97.584% and Consonants Accuracy was found to be 97.739% using the Resnet18 model with preinitilized weights.
Optimizers used was Adam and Crossentropy loss Function.
