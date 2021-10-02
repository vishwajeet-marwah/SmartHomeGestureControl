
# Smart Home Gesture Application Control - Part 2

Key files used to run this application are:

**main.py**

Contains the code to extract the frame and then the feature vectos from the training and testing data sets. Uses cosine similarity to predict the gesture number.

**handshape_feature_extractor.py**

Existing code file. This file contains the class HandShapeFeatureExtractor which uses a CNN model that is trained for hand gestures and has the method to extract feature vectors.

**frameextractor.py**

Existing code file. This file contains methods to extract the middle frame and store it to a folder location.

**gestures_trained_cnn_model.h5**

Existing file. This file contains the CNN model.


In addition to the above files, the training and test data is stored in "**traindata**" and "**testdata**" folders, respectively. The frames for the training and test data are stored within the sub-folder "**frames**" in each of the "traindata" and "testdata" folders, respectively. 



To run the program, simply run the main.py python file.
