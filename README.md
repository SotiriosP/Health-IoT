# Health-IoT
# Activity Recognition System using Accelerometer Signals and Machine Learning

# Summary
Activity recognition from accelerometer signals has numerous practical applications, including human-computer interaction, healthcare, and sports monitoring. In this project, the problem of activity recognition was approached as a machine learning task, with the aim of developing a robust activity recognition system from accelerometer signals. 

The dataset used in this study was obtained from the work of Shoaib et al. [1]. The dataset consists of recordings from 10 participants who used cell phones in different body positions while performing various activities. 

The signals were preprocessed by applying a high-pass Butterworth filter with a cutoff frequency of 1 Hz (-3dB) and 10 features were extracted from each window. The SVM classifiers with a Radial Basis Function (RBF) kernel were trained using the Leave-One-Subject-Out evaluation method. The goal of this study was to evaluate the performance of the classification model and identify the activities that could be confused by the algorithm.

#


# Dataset
[1] Muhammad Shoaib, Stephan Bosch, Ozlem Incel, Hans Scholten, and Paul Havinga. “A survey of
online activity recognition using mobile phones”. In: Sensors 15.1 (2015), pp. 2059–2085.
