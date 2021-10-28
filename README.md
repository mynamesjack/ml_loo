
Leave-One-Out classification on a 1d array.

For each object in the array, we remove it and calculate the treshold of the remaining objects. Then we use that treshold to classify the object that we removed.
Each object has a pre-assigned label and we can use the newly assigned label to calculate the error rate.

I've created a function that will do this. You only need to supply the one-dimensional array and the labels. Then call the function providing the data and the labels to receive the error rate using the leave-one-out method. 

Leave One Out is a form of k-fold cross validation. Using this method we get k different results, with k being the number of objects in the data set. We then calculate the average of correct results for the total error rate.
