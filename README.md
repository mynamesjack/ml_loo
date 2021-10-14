
Leave-One-Out classification on a 1d array.

For each object in the array, we remove it and calculate the treshold of the remaining objects. Then we use that treshold to classify the object that we removed.
Each object has a pre-assigned label and we can use the newly assigned label to calculate the error rate.
