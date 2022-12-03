# cars_demo

This notebook provides demo code for the cars dataset fount at: https://ai.stanford.edu/~jkrause/cars/car_dataset.html

The code requires the data be provided, decompressed in the following way:

cars_train folder: Contains all the training images
devkit folder: Contains the devkit. Most importantly, contains the train_perfect_preds.txt file which is assumed to be the labels for the data

NOTE: The devkit folder contains a README file which states that the labels are in the cars_train_annos.mat file. The format of this mat file was not found to match the format described in the README.

Model performance in step 6 was found to not improve with more labelled data. In fact, the model performed worse than random. This may be due to a label issue, or some other issue. Due to time constraints this could not be investigated further.

All functions are working as required, although the performance is not to the standard expected. This solution was loaded before the final training run was complete out of concern for a possible power outage (there is a severe storm in Ottawa). I'll upload the final version if possible.
