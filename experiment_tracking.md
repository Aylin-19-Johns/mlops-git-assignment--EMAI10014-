## Manual Experiment Tracking Table
| Experiment ID | Model Type | Hyperparameters | Preprocessing Steps | Feature Selection | Train/Test Split | Precision | AUC Score |
|--------------------|---------------------|------------------------|----------------------------|-------------------------|----------------------|--------------|---------------|
| EXP-01 | Decision Tree | Default | None | All features | 80/20 | 0.92 | 0.95 |
| EXP-02 | Decision Tree | Max depth = 3 | None | All features | 80/20 | 0.89 | 0.91 |
| EXP-03 | KNN | k = 3 | Standard Scaling | All features | 80/20 | 0.90 | 0.93 |
| EXP-04 | KNN | K = 7 | Standard Scaling | Selected | 80/20 | 0.87 | 0.89 |