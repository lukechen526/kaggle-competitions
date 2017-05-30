# Invasive Species Monitoring competition
## Overview
[Kaggle page](https://www.kaggle.com/c/invasive-species-monitoring)

In this playground competition, Kagglers are challenged to develop algorithms to more accurately identify whether images of forests and foliage contain invasive hydrangea or not. Techniques from computer vision alongside other current technologies like aerial imaging can make invasive species monitoring cheaper, faster, and more reliable.

Acknowledgments

Data providers: Christian Requena Mesa, Thore Engel, Amrita Menon, Emma Bradley.

## Data
The data set contains pictures taken in a Brazilian national forest. In some of the pictures there is Hydrangea, a beautiful invasive species original of Asia. Based on the training pictures and the labels provided, the participant should predict the presence of the invasive species in the testing set of pictures.

### File descriptions

* train.7z - the training set (contains 2295 images).
* train_labels.csv - the correct labels for the training set.
* test.7z - the testing set (contains 1531 images), ready to be labeled by your algorithm.
* sample_submission.csv - a sample submission file in the correct format.

### Data fields

* name - name of the sample picture file (numbers)
* invasive - probability of the picture containing an invasive species. A probability of 1 means the species is present.
