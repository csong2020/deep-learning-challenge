# deep-learning-challenge
Module 21 Challenge

The "charity" file was imported, cleaned of non-beneficial columns, and binned.
The data was then split and trained in a neural network model. Accuracy was determined to be 0.732, which means the model could be improved but is not the worst thing in the world. Three alternative models were attempted that increased the hidden layers to three (0.728), increased the hidden layers to three and increased the epoch iterations to 400 (0.724), and decreased the epoch iterations to 50 (0.723). There were not any noticeable changes in accuracy, unfortunately. Perhaps increasing the training set or reducing it would increase our accuracy.

Finally, the neural network HDF5 file was exported to the Resources folder.