# Pattern-Recognition-Project
Rumor Identification And Classification Using Machine Learning Techniques On Social Media Content

# Introduction
A rumor is a false allegation with no identifiable source,
even if its ideological or partisan roots and intentions are
clear. Rumor identification is becoming increasingly crucial
in combating rumors’ detrimental effects . Anyone with
the ability to influence and appear as news can disseminate
rumors online. Most significantly, it might be challenging
to recognize between accurate and fraudulent information,
especially when the data appears to be well-formatted and
structured. Because it is hard to personally verify such a
large amount of tweets and posts floating around, there
is a growing demand for machine learning algorithms to
help with rumor validity evaluation.

# Dataset
The dataset for our study is collected from the Activeloop
website in order to identify and classify rumors in social
media posts. ”LIAR Dataset” is a benchmark dataset [2]. LIAR
dataset is a rumor identification dataset that includes 12.8K
human-labeled short statements from politifact.com’s API,
with each statement rated for authenticity by a politifact.com
editor. The data is divided into 14 columns and 12860 rows.
We discovered duplicate labels and consolidated the full-flop,
half-flip, and no-flip labels into false, half-true, and true labels.
For the honesty evaluations, we examine six fine-grained
labels: pants-on-fire, false, barely true, half-true, mainly true,
and true

# Data Preprocessing
A. Data Cleaning
B. Removed unneeded data
C. Label Encoding
D. Balancing Imbalanced Data

# Methodology
1)Labelled Data Collection
2) Input Text
3) Data Preprocessing and Visualization
4) Text Preprocessing
5) Train Test Split
6) Feature extraction
7) Model Implementation on Training Data: Logistic
Regression, Support Vector Machines (SVM), Decision
Trees, Random Forest models, and Multinomial Naive
Bayes are implemented on training data.

# Conclusion
 For multi-class
detection, among the models, Multinomial Na¨ıve Bayes has
performed the best giving an accuracy of 25.24% and also giving
the highest precision recall and f1 score.

