# Data Leakage

Data Leakage happens when information from the future or testing data accidentally enters the training process.

This causes unrealistically high accuracy.

The model appears excellent during testing but fails in real-world deployment.

---

## Prevention

- Keep training and testing data separate.
- Never use future information.
- Use proper pipelines.
- Apply preprocessing only on training data.
