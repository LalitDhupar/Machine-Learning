# Video-Memorability-Prediction
Predict short-term and long-term memorability scores using either the video features like C3D, HMP or semantic feature like the captions (text explaining the video content).

# Dataset
Datset of 6000 short soundless video clips along with video features like C3D, HMP and semantic features were provied. Ground truth of Short-term Memorability scores, Long-term memorability scores and number of annotations which represents the number of people participated in the experiment were given as part of the assignment. 

# Approach
Captions, C3D and HMP features of the vidoes were individually used to train RNN model. Captions feature was pre-processed before training the model. All the punctuation marks were replaced with a space, and all the alphabets in the captions were set to lower case. Using tokenization, the words in the captions were converted into vectors by mapping words from the corpus to numbers. In addition, sequence encoding was performed and padding was applied to makeup for the unequal length of the captions. 

# Results
 Results showed that short term memorability predictions are more reliable and accurate compared to long term predictions. Captions being the only semantic feature outperformed the models trainined on C3D and HMP features.
