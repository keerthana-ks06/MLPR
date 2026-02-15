# MLPR
# Lab 5 – k-Means Clustering on Face Images

## Aim
To cluster detected human faces using k-Means clustering based on hue and
saturation features extracted from the HSV color space.

## Methodology
- Faces were detected using Haar Cascade classifiers.
- Detected faces were converted to HSV color space.
- Mean hue and saturation values were extracted as features.
- k-Means clustering (k=2) was applied.
- A template image was classified based on the nearest cluster.

## Results
The faces were grouped into two clusters based on color similarity.
Cluster centroids represent the average hue-saturation values of each group.

## Conclusion
This experiment demonstrates unsupervised learning using k-Means clustering
and shows how color-based features can be used for simple image classification.

## Files
- `Lab_5_KMeans_Face_Clustering.ipynb`


