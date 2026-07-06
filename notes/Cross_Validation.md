# Cross Validation

Cross Validation is a technique used to evaluate machine learning models more reliably.

Instead of using only one train-test split, the dataset is divided into multiple folds.

The model is trained and validated several times.

---

## K-Fold Cross Validation

The data is divided into K equal parts.

One fold is used for validation.

The remaining folds are used for training.

This process repeats until every fold has been used once.

---

## Stratified Cross Validation

Used for classification problems.

It ensures that every fold contains the same class distribution as the original dataset.

This is especially useful for imbalanced datasets.
