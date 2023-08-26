## Classifying Emotions of Turkish Music using KNN Classification
In this project, we will use the knn classification algorithm to classify songs into the following emotions:

Happy: the feeling of pleasure
Sad: the feeling of unhappiness
Angry: The strong feeling of dislike towards something
Relaxed: The feeling of being calm (Oxford)

Through this project, we aim to further explore this topic by investigating how different elements of music can be associated with emotions, and how we can use these elements to classify the primary emotion of a song. The data set “Turkish Music Emotion” by Mehmet Bilal Er explores this question. He used fifty variables over 400 Turkish songs and categorized each song into one of four emotions: Happy, Sad, Angry, and Relaxed.

From Mehmet Bilal Er’s dataset, six variables were selected to act as predictors in this report:

Low Energy Mean: percentage of frames with less energy than usual
Zero Crossing Rate Mean: times the waveform crosses zero
Attack Time Mean: peaks passed through the compressor
Pulse Clarity Mean: how easily the song’s rhythm can be perceived
Spectral Spread Mean: standard deviation of spectral centroid
Harmonic Change Detection Function Mean: key and chord transitions
With this, we hypothesize that the average Low Energy, Zero Crossing Rate, Attack Time, Pulse Clarity, Spectral Spread, and Harmonic Change Detection will be able to accurately predict the main emotion of a song, Happy, Sad, Angry, and Relaxed, using the K-nearest neighbors classification algorithm.
