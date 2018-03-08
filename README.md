# Decision_Tree_Mini_Project
Creating a Decision Tree classifier for email sender prediction using a text-learning machine learning algorithm in Python.

---
## Usage Instructions

Go to the tools directory and run the `startup.py` file which will check for all the dependencies required and download the dataset.

The dataset is 423 MB in size, so it may take some time to download.

Once the dataset download is complete, a new folder **maildir** will appear in the root directory of the project containing all the required data for the project.

---
## Code file desciptions

* accuracy_min_samples_split40.py

Setting the classifier parameter `min_samples_split=40` what is the accuracy of the classifier?

* accuracy_selector_percentile1.py

Go to `../tools/email_preprocess.py` and find the line that looks like `selector = SelectPercentile(f_classif, percentile=10)` . Change percntile from 10 to 1 and retrain the classifier on 1% of the available features and find the accuracy.

* no_of_features

The features are organized as a NumPy array. Find the number of features for training.

* no_of_features_selector_percentile1.py

Go to `../tools/email_preprocess.py` and find the line that looks like `selector = SelectPercentile(f_classif, percentile=10)` . Change `percentile` from 10 to 1 and now find the number of features for training.
