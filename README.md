# Principal component analysis
This task involves exploring methods of dimensionality reduction. We will be
looking into PCA (principal component analysis), for this task. Principal Component Analysis (PCA) is the general name for a technique which uses sophisticated underlying mathematical principles to transform a number of possibly
correlated variables into a smaller number of variables called principal components. IEEE Signal Processing Magazine (Accessible through college internet)
Use only NumPy, Pandas, matplotlib, and Plotly libraries for the tasks..
## 1.1 PCA
This task requires you to implement Principal Component Analysis and perform
dimensionality reduction on a given dataset(s). The list of subtasks is given
below.
1. Perform dimensionality reduction on the IIIT-CFW dataset, varying the
number of principle components. We have given the script to pre-process
the data and to get the necessary information from the image Script.
2. Plot the the relationship between the cumulative explained variance and
the number of principal components. The x-axis of the plot typically
represents the number of principal components, and the y-axis represents
the cumulative explained variance.
3. Perform the dimensionality reduction on features that you have used for
assignment 1 (pictionary dataset) and show the metrics you have shown for
the assignment 1. Compare the results and write down the observations
in the MARKDOWN.

4. Observe the impact of dimensionality reduction on the dataset. Use a classifier on the dataset pre and post-dimensionality reduction (if the number
of features of the dataset is n, perform dimensionality reduction varying
the principal components from 1 to n) and note the accuracies of the
classifier. You are free to use external libraries for the classifier.
## 1.2 Pictionary Dataset
This task is to perform the PCA on the Pictionary Dataset (Dataset).The attachment also contains the description for the Dataset. Perform PCA for both
drawer and guesser.
1. Plot the above features with respect to the obtained PCA axes.
2. What does each of the new axes that are obtained from PCA represent?
