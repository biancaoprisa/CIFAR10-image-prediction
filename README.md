Three distinct datasets have been created:
• The first dataset contains the latter six classes, with 5,000 training samples per class.
• The second dataset contains the first four classes, with 500 training samples per class.
• The third dataset is imbalanced, consisting of the other two datasets combined. Therefore, this
dataset contains ten classes, with only 500 samples retained from the first four classes.
For the first part of the project, I have performed image classification on the six class dataset. Therefore, I have developed a convolutional neural network and trained it on the six class data set, and I have used the test data for validation.
For the second part of the project, I have used the four class and the imbalanced datasets. The purpose was to develop two convolutional neural nets and explore how different model parameters and architectures affect the validation accuracy for each class when trained on each of the datasets. Next, I have discussed possible solutions for situations where we encounter an imbalanced dataset.
The latter part of the project was the most interesting. I've develop a convolutional neural network and trained it on the six class dataset. Then, I froze all layers apart from the last one and performed transfer learning on the four class dataset.
For a full report, please check the Project-Tensorflow file in this repository.
