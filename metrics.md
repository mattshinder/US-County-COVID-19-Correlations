# COVID 19 County Correlations
## Model Metrics
### Mean Shift Clustering
Bandwidth was determined by estimate_bandwidth() on our own data.
### PCA
Use the scaled data to get better results.
### KMeans Clustering
Initial model created using k=3 and random_state=42
Later model use k=10 based off of calculated WCCS value
For the last model (second approach), use k=7

### Libaries
Mean Shift: sklearn.cluster
PCA: sklearn.decomposition
KMeans: scklearn.cluster
