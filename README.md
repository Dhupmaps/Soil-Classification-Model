## SVM-Based Soil Classification from Image Analysis

This project presents a machine learning model for classifying soil types from digital images. It employs a Support Vector Machine (SVM) to distinguish between categories such as Silty Sand, Sandy Clay, and Peat.

## The methodology follows a robust pipeline:

Image Preprocessing: Raw soil images are refined using low-pass and Gabor filtering for texture analysis and color quantization to standardize the color space.

Feature Extraction: Key textural and color features are extracted using statistical methods, including mean amplitude, standard deviation, and HSV color histograms.

Classification: The extracted features are fed into an SVM classifier to predict the soil category with high accuracy.

The model was trained and validated on a diverse dataset of 175 soil images, ensuring its robustness for real-world applications.
