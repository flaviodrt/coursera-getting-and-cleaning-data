## CodeBook

1. There's a function called `download.data()` that will download the dataset.
2. The two datasets are merged with `rbind`
3. Extract the mean and std with grep of each measurement
4. A new dataset containing the activity name with `rbind`
5. Update the indexes with activity label
6. Create the tidy dataset 
