# TechcrunchPostsMulticlassPostsClassification
In this notebook I search the best classifier and its parameters for posts multi-class classifications based on authorship attributes

The best method is LinearSVC(C=1). The worse is BernoulliNB(alpha=0.1). There is a difference between binary and multi-class classifications. Bernoulli Naive Bayes has the same or better scores then LinearSVC etc
SVC with the linear kernel shows worse result then LinearSVC. This is also different from binary classification. LinearSVC uses "one-vs-rest" (default) and SVC uses "one-vs-one" for multi-class. And SGDClassifier uses "one-vs-all" for multi-class classification
