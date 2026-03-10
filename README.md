# K-Nearest-Neighbors

## Download the Dataset

The dataset is available [here](https://d32aokrjazspmn.cloudfront.net/materials/ML_Houses_clean.csv). Download it using the following commands and save it to the `data` folder in the `01-KNN` directory:

``` bash
curl https://d32aokrjazspmn.cloudfront.net/materials/ML_Houses_clean.csv > data/houses_clean.csv
```

## Dataset

- The dataset is a selection of features from the Houses dataset.
- Most features have already been processed.
- The target is the selling price of the houses.

## Exercise

This exercise breaks down the KNN algorithm and its mechanics. You will do the following:

- Explore its sensitivity to scale
- Intentionally perform overfitting
- Fine-tune the K parameter

Finally, compare its performance with Linear Regression and select the model best suited to the task.
