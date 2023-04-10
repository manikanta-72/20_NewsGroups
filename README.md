# 20_NewsGroups
Analysis of Text Classification task on 20 Newsgroups dataset using multiple models. Models analyzed were KNN, Naive Bayes(NB), Support Vector Machines(SVM), Vanilla Neural Network(NN), Hierarchial Attention Network and Text CNN

# Results
The following are the accuracies of different models on Text Classification Task.
![alt text](https://github.com/manikanta-72/20_NewsGroups/blob/main/Results/20_news_groups.png)

# Conclusion
As expected, KNN performed poorly among all the models as it’s a very simple model and because of a large number of feature dimensions. Neural networks performed relatively better than KNN as they can extract complex patterns within the dataset. But Neural Networks can get stuck at local minima and fail to converge to global minimums. SVM models can use higher dimensional feature spaces with the help of kernels like RBF functions and it converges to the global minimum. With help of Spatial and sequential models, we can classify the models better. Sequential Models like HAN are sensitive to weight initialization because of this, they may be under-performing. We can achieve higher accuracy with the Text CNN model. It is observed that Text Classification tasks depend on feature extraction and understanding the context of word occurrences.
