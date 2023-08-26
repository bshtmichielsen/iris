# Nearest Neigbors with the Iris dataset

This project is used as the **week 1** exercise in a Machine Learning course.

Project *iris* demonstrates using Nearest Neighbor to classify iris flowers.

## Exercise

Leave the notebook as is, and just add at the bottom. Do not fiddle with the given parts but copy and paste code from earlier cells into new cells below in order to change it and try something else. A notebook is not a code file, it is ok to repeat pieces of code.

### Different results

If you re-run this notebook a few times, without changing anything, you sometimes get slightly different results. Add a text cell in which you explain why you believe this is. Compare your answer with some fellow students. Did they have the same opinion? If not, explain the difference. 

### Feature selection

In the section about feature selection we selected `Petal Length` and `Petal Width` as our two features to base the modelling on. Copy and past the given code from earlier cells as to pick any other two features, train another Nearest Neighbors model and compare the results with the given model. Did it work beter? If yes, why, if no, why? What happens if you select 3 features?
 
### Hyperparameter n_neighbors

The constructor of the kNeighborsClassifier has an optional hyperparameter named `n_neighbors`, which by default is `5`. Try providing a value of `2` for this parameter and see if this makes any difference. Then provide a value of `85` for this parameter and note any differences. Which of those 3 values [`5`, `2`, `85`] would you say gives the best results and why?
