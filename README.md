# Fingerprint-Spoof-Detector-Based-on-LBP-and-HOG
Assignment-2: Computer Vision Spring-2021 


**Title:  Fingerprint Spoof Detector Based on LBP and HOG**

**Abstract:** Fake fingers can be easily fabricated using commonly available materials, such as latex,
silicone and gelatin, with the fingerprint ridges of an individual engraved on it. These fake fingers
can then be used by an adversary to launch a spoof attack by placing them on a fingerprint sensor
and claiming the identity of another individual. The success rate of such spoof attacks can be upto
70%. Fingerprint spoof detection algorithms have been proposed as a countermeasure against
spoof attacks. A fingerprint spoof detector is a pattern classifier that is used to distinguish a live
finger from a fake (spoof) one in the context of an automated fingerprint recognition system. Most
liveness detectors are learning-based and rely on a set of training images.
Project Goal: To develop a two-class fingerprint spoof detector that uses Local Binary Patterns
(LBP) and Histogram of Oriented Gradients (HOG) features along with Support Vector Machines
(SVM) to distinguish live fingerprints images from spoof samples.

**Data:** Training and Testing Live and Fake fingerprint samples are located at:
https://drive.google.com/drive/folders/1nLWXD8wR7zD4tI0udk2GN6XC9EqIF8PR?usp=shari
ng
- Training data: Spoof_data/ Training Biometrika Live/ live (Positive class)
Spoof_data/ Training Biometrika Spoof/ Training Biometrika Spoof/ spoof (Negative Class)
- Testing data: Spoof_data/ Testing Biometrika Live/ live (Positive class)
Spoof_data/ Testing Biometrika Spoof/ Testing Biometrika Spoof / spoof (Negative Class)
Method:
- Extract LBP and HOG features from live and spoof images from training and testing set.
- Train a two-class SVM on LBP and HOG features from live and fake samples from the training
set along with the label 0/1.
- Test the SVM on LBP and HOG features from live and fake samples from the testing set
- Report precision, recall and accuracy of the SVM when evaluated on the test set. Compare the
performance of HOG and LBP features.
