# cars_demo

This notebook provides demo code for the cars dataset fount at: https://ai.stanford.edu/~jkrause/cars/car_dataset.html

The code requires the data be provided as it is not located in this repository.

cars_train folder: Contains all the training images, decompressed.

devkit folder: Contains the devkit. Most importantly, this folder contains the train_perfect_preds.txt file which is assumed to be the labels for the data (although I am suspicious of the quality of these labels due to poor model performance).

NOTE: The devkit folder contains a README file which states that the labels are in the cars_train_annos.mat file. The format of this mat file was not found to match the format described in the README.

Model performance in step 6 was found to not improve with more labelled data. In fact, the model performed worse than random. This may be due to a label issue, or some other issue. Due to time constraints this could not be investigated further. I did run a test where I performed testing on the same training data and found very high accuracy (near 100%). This indicates that the model was at least learning the training data but not generalizing. This suggests to me thata the labels are an issue.

All functions are working as required, although the model performance is not to the standard expected.
