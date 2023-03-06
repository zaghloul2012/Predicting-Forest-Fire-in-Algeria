
# Student Performance 

## Introduction
Forest fire is a critical concern over the world, each year millions of hectares are destroyed all around the word. Algeria is one of the countries affected by this phenomenon, mainly in summerForest fires cause economic and ecological damage, as well as human life threat. Predicting forest fires is crucial to mitigate this threat.
You can read more through the paper puplished in 2020 on [Predicting Forest Fire in Algeria Using Data Mining Techniques: Case Study of the Decision Tree Algorithm](https://www.researchgate.net/publication/339062373_Predicting_Forest_Fire_in_Algeria_Using_Data_Mining_Techniques_Case_Study_of_the_Decision_Tree_Algorithm/download)

## Motivation
In my project, I aim to develop a more accurate system for forest fire prediction by testing and comparing various classification models. In addition to the decision tree-based system proposed in existing literature, I will assess the performance of logistic regression, k-nearest neighbors, support vector machine, kernel SVM, Naive Bayes, random forest classification, and other classification models.

To identify the most significant features for predicting forest fires, I will also conduct tests based on the relationship between the independent variables (features) and the dependent variable (target). Specifically, I will utilize box plots to identify the variables that may be the best predictors and also conduct the Wald significance test.

## Dataset
The dataset includes 244 instances that regroup a data of two regions of Algeria,namely the Bejaia region located in the northeast of Algeria and the Sidi Bel-abbes region located in the northwest of Algeria. 122 instances for each region.

Data can be downloaded from [here](https://archive.ics.uci.edu/ml/datasets/Algerian+Forest+Fires+Dataset++)


## Model Development 
To select potential predictor features for our target variable, we first examined the relationship between each independent variable and the target variable using boxplots. We looked for significant variations in mean, median, and distribution between the two categories.

Next, we developed different classification models to assess their suitability for our case. These models included logistic regression, k-nearest neighbors, support vector machine, kernel SVM, naive Bayes, decision tree classification, and random forest classification.

1. Logistic regression: This model is a popular linear classifier that uses a sigmoid function to model the probability of the target variable. It is simple, interpretable, and can handle large datasets.
2. K-nearest neighbors: This model is a non-parametric classifier that assigns a class based on the k closest data points. It is flexible and can capture complex relationships between variables.
3. Support vector machine: This model aims to find a hyperplane that separates the two classes with the maximum margin. It can handle non-linear data by using kernel functions.
4. Kernel SVM: Similar to SVM, but can handle non-linearly separable data by using kernel functions.
5. Naive Bayes: This model is a probabilistic classifier that assumes independence between the features. It is fast, simple, and can handle high-dimensional data.
6. Decision tree classification: This model uses a tree-like structure to classify data by splitting it based on the most informative features. It is interpretable and can capture non-linear relationships.
7. Random forest classification: This model is an ensemble method that creates multiple decision trees and combines their predictions. It can handle high-dimensional data and reduces overfitting.

## Results
Using these features, our model achieves an accuracy of 95% along with precision score of 0.94, recall score of 0.92, and f1 score of 0.96. These metrics outperform the results reported in the literature for the same decision tree classifier model.

We developed different models most of them can beat the one in the literature. 

Here are the results of the literature that we beat
![Literature Results](/pictures/literature.png "Literature Results")

And our results for models based on the selected features 
![Selected Feature Results](/pictures/boxplot features.png "Selected Feature Results")

And our results for models based on the all features 
![All Feature Results](/pictures/all features.png"All Feature Results")


## Acknowledgements

 - [Predicting Forest Fire in Algeria Using Data Mining Techniques: Case Study of the Decision Tree Algorithm](https://www.researchgate.net/publication/339062373_Predicting_Forest_Fire_in_Algeria_Using_Data_Mining_Techniques_Case_Study_of_the_Decision_Tree_Algorithm)
 
 - [Algerian Forest Fires Dataset Data Set](https://archive.ics.uci.edu/ml/datasets/Algerian+Forest+Fires+Dataset++)

 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## Feedback

If you have any feedback, please reach out to us at youssef.zaghloul@ejust.edu.eg

