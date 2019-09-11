
## Purpose:

This was the final assignment for University of Michigan's 'Applied Machine Learning with Python' course. To get 100% on the assignment, it was necessary to get an AUC score >0.75 when submitting predictions on the test set.

It turns out that on my first try, I was able to pass this threshold, using a few feature columns, and running GridSearchCV with a RandomForestClassifier. This was quite anti-climactic for me.

The purpose of this project is to try out some other features, and scoring with AUC (intead of default accuracy). I would like to see if I can get a score higher than 0.765 on an AUC metric. I will keep using Random Forests, and see how far I can push them.

In the end, it was found that adding more features did not improve the model much. This was coroborated by other students in the class (on the course discussion board). The maximum score seen was
an AUC of 0.82.
