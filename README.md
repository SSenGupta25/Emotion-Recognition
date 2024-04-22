# Multimodal Emotion Recognition using Opensmile and Deepface on RAVDESS dataset

In this research, we developed an Emotion Recognition system using two modalities: speech and facial expressions. The speech emotion recognizer (SER) utilized Opensmile to extract features from 1344 audio files, which represented 7 different emotions expressed by 24 actors. We achieved the best accuracy by applying PCA to reduce the dimensionality of the features and training them using a Multi-layer Perceptron (MLP) as a supervised learning algorithm.

Similarly, for the facial emotion recognizer (FER), we processed 1344 videos of 24 actors. Each video was divided into 4 frames, and Deepface was employed to extract Action Units from each frame. PCA was again applied to reduce the feature dimensionality, followed by training the dataset using MLP.

Finally, we combined the features extracted from both modalities (audio and video) and achieved an overall accuracy of 82.60% for classifying the 7 emotions in the dataset. Our results demonstrate that these modalities contain valuable information for detecting users' emotional states, and their combination significantly improved the performance of the system.
