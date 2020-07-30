# Spoken digit recognition

The dataset is a subset of the Tensorflow speech commands dataset that includes other sound recordings besides the digits 0–9.

The project has three approaches to classifying the recordings:
1. Logistic Regression using five extracted features - 76.19% accuracy.
2. Logistic Regression using only MFCCs - 95.56% accuracy.
3. CNN using Mel spectrogram - 95.81% accuracy.

There are five .ipynb files:
* Feature extraction - The necessary CSV files and features used by the three approaches are extracted.
* Feature visualization - The features are plotted for two examples in each class.
* Spokendigit-Five features - Implementation of logistic regression using five extracted features.
* Spokendigit-MFFCs - Implementation of logistic regression using MFCCs.
* Spokendigit-CNNs - Implementation of CNN using Mel spectrogram.

Medium article - [Torch: Spoken digits recognition from features to model.](https://medium.com/@ayisha.d/torch-spoken-digits-recognition-from-features-to-model-357209cd49d1?source=friends_link&sk=5bc534144c970d58c9dcf7fc42c1c70b)
