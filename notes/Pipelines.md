# Machine Learning Pipeline

A Pipeline connects multiple machine learning steps into one workflow.

Instead of writing separate code for every step, the pipeline performs everything automatically.

---

## Pipeline Steps

1. StandardScaler
2. PCA
3. Machine Learning Model

Each step automatically passes its output to the next step.

---

## Advantages

- Cleaner code
- Easier maintenance
- Prevents data leakage
- Works perfectly with GridSearchCV
