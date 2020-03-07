# rescale
A function that can transform features by scaling each feature to a given range. The input should be (input list, new minimum value, new maximum value). This is more light weight and easy to use than sklearn.preprocessing.MinMaxScaler. This function can simply and quickly rescale each element of the input list into a new value within the range, and generate a new list.
